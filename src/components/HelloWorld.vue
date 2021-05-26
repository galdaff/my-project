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
                        class="company"
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
                        class="username"
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
                        class="email"
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
                        class="firstname"
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
                        class="lastname"
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
                        class="address"
                      />
                      <!---->
                    </div>
                  </div>
                </div>
                <div class="row">
                  <div class="col-md-4">
                    <div class="form-group">
                      <label class="control-city"> City </label><br/>
                      <!---->
                      <input
                        aria-describedby="addon-right addon-left"
                        type="text"
                        placeholder="City"
                        class="city"
                      />
                      <!---->
                    </div>
                  </div>
                  <div class="col-md-4">
                    <div class="form-group">
                      <label class="control-country"> Country </label><br/>
                      <!---->
                      <input
                        aria-describedby="addon-right addon-left"
                        type="text"
                        placeholder="Country"
                        class="country"
                      />
                      <!---->
                    </div>
                  </div>
                  <div class="col-md-4">
                    <div class="form-group">
                      <label class="control-postalcode"> Postal Code </label><br/>
                      <!---->
                      <input
                        aria-describedby="addon-right addon-left"
                        type="number"
                        placeholder="ZIP Code"
                        class="postalcode"
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
                        class="aboutme" 
                        rows="2"
                        cols="105"
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
.col-md-8 {
  position: relative;
  width: 100%;
  min-height: 1px;
  padding-right: 15px;
  padding-left: 15px;
  width: 803px;
  height: 600px;
}
.form-group {
  display: block;
}
.col-md-5 .col-md-3 .col-md-4{
      position: relative;
    width: 100%;
    min-height: 1px;
    padding-right: 15px;
    padding-left: 15px;
}
.card {
  position: relative;
  display: flex;
  flex-direction: column;
  min-width: 0;
  word-wrap: break-word;
  background-clip: border-box;
  border-radius: 0.25rem;
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
  margin-right: 2rem;
  margin-top: 1rem;
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
  width: 300px; 
  height: 40px; 
  margin-right: 0.5rem
} 
.username {
  width: 180px; 
  height: 40px; 
  margin-right: 0.5rem
}
.email {
  width: 236px; 
  height: 40px;
} 
.firstname {
  width: 364px; 
  height: 40px; 
  margin-right: 0.2rem;
} 
.lastname {
  width: 364px; 
  height: 40px;
}
.address {
  width: 748px; 
  height: 40px;
}
.city {
  width: 236px; 
  height: 40px; 
  margin-right: 0.5rem;
}
.country {
  width: 245px; 
  height: 40px; 
  margin-right: 0.5rem;
}
.postalcode {
  width: 236px; 
  height: 40px;
}
.avatar {
  border-radius: 50%;
  width: 110px;
  height: 110px;
  margin-left: 6rem;
}
</style>

<script>
export default {
  mounted() {
    console.log("mounted");
  },
};
</script>
