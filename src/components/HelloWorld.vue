<template>
  <div class="container">
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-8">
          <div class="card">
            <!---->
            <div class="card-header">
              <h4 class="card-title">Edit Profile</h4>
            </div>
            <div class="card-body">
              <form>
                <div class="row">
                  <div class="col-md-5">
                    <div class="form-group">
                      <label class="control-company"> Company </label><br/>
                      <!---->
                      <input
                        aria-describedby="addon-right addon-left"
                        type="text"
                        disabled="disabled"
                        placeholder="Light dashboard"
                        class="company txt"
                      />
                      <!---->
                    </div>
                  </div>
                  <div class="col-md-3">
                    <div class="form-group">
                      <label class="control-username"> Username </label><br/>
                      <!---->
                      <input
                        aria-describedby="addon-right addon-left"
                        type="text"
                        placeholder="Username"
                        class="username txt"
                      />
                      <!---->
                    </div>
                  </div>
                  <div class="col-md-4">
                    <div class="form-group">
                      <label class="control-email"> Email </label><br/>
                      <!---->
                      <input
                        aria-describedby="addon-right addon-left"
                        type="email"
                        placeholder="Email"
                        class="email txt"
                      />
                      <!---->
                    </div>
                  </div>
                </div>
                <div class="row">
                  <div class="col-md-6">
                    <div class="form-group">
                      <label class="control-firstname"> First Name </label><br/>
                      <!---->
                      <input
                        aria-describedby="addon-right addon-left"
                        type="text"
                        placeholder="Firstname"
                        class="firstname txt"
                      />
                      <!---->
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="form-group">
                      <label class="control-lastname"> Last Name </label><br/>
                      <!---->
                      <input
                        aria-describedby="addon-right addon-left"
                        type="text"
                        placeholder="Lastname"
                        class="lastname txt"
                      />
                      <!---->
                    </div>
                  </div>
                </div>
                <div class="row">
                  <div class="col-md-12">
                    <div class="form-group">
                      <label class="control-address"> Address </label><br/>
                      <!---->
                      <input
                        aria-describedby="addon-right addon-left"
                        type="text"
                        placeholder="Home Address"
                        class="address txt"
                      />
                      <!---->
                    </div>
                  </div>
                </div>
                <div class="row">
                  <div class="col-md-7">
                    <div class="form-group">
                      <label class="control-city"> City </label><br/>
                      <!---->
                      <input
                        aria-describedby="addon-right addon-left"
                        type="text"
                        placeholder="City"
                        class="city txt"
                      />
                      <!---->
                    </div>
                  </div>
                  <div class="col-md-7">
                    <div class="form-group">
                      <label class="control-country"> Country </label><br/>
                      <!---->
                      <input
                        aria-describedby="addon-right addon-left"
                        type="text"
                        placeholder="Country"
                        class="country txt"
                      />
                      <!---->
                    </div>
                  </div>
                  <div class="col-md-7">
                    <div class="form-group">
                      <label class="control-postalcode"> Postal Code </label><br/>
                      <input
                        aria-describedby="addon-right addon-left"
                        type="number"
                        placeholder="ZIP Code"
                        class="postalcode txt"
                      />
                      <!---->
                    </div>
                  </div>
                </div>
                <div class="row">
                  <div class="col-md-12">
                    <div class="form-group">
                      <label>About Me</label><br/>
                      <textarea
                        placeholder="Here can be your description"
                        class="aboutme txt" 
                        rows="2"
                        cols="89"
                      ></textarea>
                    </div>
                  </div>
                </div>
                <div class="text-center">
                  <button
                    type="submit"
                    class="btnUpdate"
                  >
                    Update Profile
                  </button>
                </div>
                <div class="clearfix"></div>
              </form>
            </div>
            <!---->
          </div>
        </div>
        <div class="col-md-4">
          <div class="card card-user">
            <div class="card-image">
              <img
                src=""
                alt="..."
              />
            </div>
            <!---->
            <div class="card-body">
              <div class="author">
                <a href="#"
                  ><img
                    src="../assets/user.jpg"
                    alt="..."
                    class="avatar"
                  />
                  <h4 class="title">
                    Mike Andrew<br />
                    <small>michael24</small>
                  </h4></a
                >
              </div>
              <p class="description text-center">
                "Lamborghini Mercy <br />
                Your chick she so thirsty <br />
                I'm in that two seat Lambo"
              </p>
            </div>
            <div class="card-footer">
              <hr />
              <div class="text-center">
                <button href="#" class="btn btn-simple">
                  <i class="fa fa-facebook-square"></i>
                </button>
                <button href="#" class="btn btn-simple">
                  <i class="fa fa-twitter"></i>
                </button>
                <button href="#" class="btn btn-simple">
                  <i class="fa fa-google-plus-square"></i>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container-fluid {
  background-color: rgb(245, 241, 241);
  height: 937px;
}
.col-md-8 {
  position: relative;
  width: 100%;
  min-height: 1px;
  padding-right: 15px;
  padding-left: 15px;
  width: 950px;
  height: 500px;
}
.form-group {
  display: block;
  margin-left: 1rem;
}
.col-md-5 .col-md-3 .col-md-4{
    position: relative;
    width: 100%;
    min-height: 1px;
    padding-right: 15px;
    padding-left: 15px;
}
.col-md-6 {
  margin-top: 2rem;
}
.col-md-7 {
  margin-top: 2rem;
}
.col-md-12 {
  margin-top: 2rem;
}
.card {
  position: relative;
  display: flex;
  flex-direction: column;
  min-width: 0;
  word-wrap: break-word;
  background-clip: border-box;
  border-radius: 4px;
  border-style: solid;
  border-width: 0.25px;
  height: 680px;
  margin: 10rem 0rem 0rem 5rem;
  background-color: rgb(255, 254, 254)
}
.card .card-body {
  padding: 15px 15px 10px;
}
.card-body {
  flex: 1 1 auto;
  padding: 1.25rem;
  height: 500px;
}
.author {
  width: 300px;
}
.card-header {
  margin-left: 1rem;
}
.row {
  display: -ms-flexbox;
  display: flex;
  flex-wrap: wrap;
  margin-right: -15px;
  margin-left: -15px;
}
.card label {
  font-size: 12px;
  margin-bottom: 5px;
  text-transform: uppercase;
}
label {
  display: inline-block;
}
.btnUpdate {
  color: #fff;
  background-color: #1dc7ea;
  opacity: 2;
  filter: alpha(opacity=100);
  float: right;
  height:44px;
  width: 135px;
  font: 16px;
  margin: 2rem 1rem 2rem 0rem;
  border-radius: 5px;
  font-size: 15px;
}
.float-right {
  float: right !important;
}
.container-fluid {
    width: 100%;
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto;
}
body {
    margin: 0;
    font-family: -apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Helvetica Neue,Arial,sans-serif;
    font-size: 1rem;
    font-weight: 400;
    line-height: 1.5;
    color: #212529;
    text-align: left;
    background-color: #fff;
}
.aboutme {
  resize: vertical;
}
.col-md-6 {
  margin-right: 0.5rem;
}
.company {
  width: 307px; 
  height: 40px; 
  margin-right: 0.5rem
} 
.username {
  width: 188px; 
  height: 40px; 
  margin-right: 0.5rem
}
.email {
  width: 244px; 
  height: 40px;
} 
.firstname {
  width: 387px; 
  height: 40px; 
  margin-right: 0px;
} 
.lastname {
  width: 387px; 
  height: 40px;
}
.address {
  width: 810px; 
  height: 40px;
}
.city {
  width: 246px; 
  height: 40px; 
  margin-right: 0.5rem;
}
.country {
  width: 257px; 
  height: 40px; 
  margin-right: 0.5rem;
}
.postalcode {
  width: 246px; 
  height: 40px;
}
.avatar {
  border-radius: 50%;
  width: 110px;
  height: 110px;
  margin-left: 6rem;
}
.txt {
  font-size: 16px;
  font-weight: normal;
}
</style>

<script>
export default {
  mounted() {
    console.log("mounted");
  },
};
</script>
