<template>
  <div class="container">
    <div class="row">
      <div class="col-md-4">
          <!-- Widget: user widget style 1 -->
          <div class="box box-widget widget-user">
            <!-- Add the bg color to the header using any of the bg-* classes -->
            <div class="widget-user-header bg-black">
              <h3 class="widget-user-username">Elizabeth Pierce</h3>
              <h5 class="widget-user-desc">Web Designer</h5>
            </div>
            <div class="widget-user-image">
              <img class="img-circle" src="../assets/user3-128x128.jpg" alt="User Avatar">
            </div>
            <div class="box-footer">
              <div class="row">
                <div class="col-sm-4 border-right">
                  <div class="description-block">
                    <h5 class="description-header">3,200</h5>
                    <span class="description-text">SALES</span>
                  </div>
                  <!-- /.description-block -->
                </div>
                <!-- /.col -->
                <div class="col-sm-4 border-right">
                  <div class="description-block">
                    <h5 class="description-header">13,000</h5>
                    <span class="description-text">FOLLOWERS</span>
                  </div>
                  <!-- /.description-block -->
                </div>
                <!-- /.col -->
                <div class="col-sm-4">
                  <div class="description-block">
                    <h5 class="description-header">35</h5>
                    <span class="description-text">PRODUCTS</span>
                  </div>
                  <!-- /.description-block -->
                </div>
                <!-- /.col -->
              </div>
              <!-- /.row -->
            </div>
          </div>
          <!-- /.widget-user -->
        </div>
<div class="col-md-4">
          <!-- Widget: user widget style 1 -->
          <div class="box box-widget widget-user">
            <!-- Add the bg color to the header using any of the bg-* classes -->
            <div class="widget-user-header bg-black">
              <h3 class="widget-user-username">Elizabeth Pierce</h3>
              <h5 class="widget-user-desc">Web Designer</h5>
            </div>
            <div class="widget-user-image">
              <img class="img-circle" src="../assets/user3-128x128.jpg" alt="User Avatar">
            </div>
            <div class="box-footer">
              <div class="row">
                <div class="col-sm-4 border-right">
                  <div class="description-block">
                    <h5 class="description-header">3,200</h5>
                    <span class="description-text">SALES</span>
                  </div>
                  <!-- /.description-block -->
                </div>
                <!-- /.col -->
                <div class="col-sm-4 border-right">
                  <div class="description-block">
                    <h5 class="description-header">13,000</h5>
                    <span class="description-text">FOLLOWERS</span>
                  </div>
                  <!-- /.description-block -->
                </div>
                <!-- /.col -->
                <div class="col-sm-4">
                  <div class="description-block">
                    <h5 class="description-header">35</h5>
                    <span class="description-text">PRODUCTS</span>
                  </div>
                  <!-- /.description-block -->
                </div>
                <!-- /.col -->
              </div>
              <!-- /.row -->
            </div>
          </div>
          <!-- /.widget-user -->
        </div>
    </div>
  </div>
</template>

<style scoped>
  *{
    box-sizing: border-box;
  }
  .container{
    width:1479px;
    display:table-cell;
  }
  .col-sm-4{
    position: relative;
    min-height: 1px;
    padding: 5px 20px;
    float: left;
  }
.col-sm-4 {
    width: 122px;
    height: 57px;
}
.col-md-4{
    position: relative;
    min-height: 1px;
    padding-right: 15px;
    padding-left: 15px;
    width: 416px;
    height:238px;
}
.widget-user .widget-user-image {
    position: absolute;
    top: 65px;
    left: 50%;
    margin-left: -45px;
}
.img-circle {
    border-radius: 50%;
    width: 90px;
    height: 90px;
}
.box-footer {
    border-top-left-radius: 0;
    border-top-right-radius: 0;
    border-bottom-right-radius: 3px;
    border-bottom-left-radius: 3px;
    border-top: 1px solid #f4f4f4;
    padding: 30px 10px 10px;
    background-color: rgb(255, 255, 255);
    display: table;
    width :386px;
    height:120px;
}
.box .border-right {
    border-right: 2px solid #f4f4f4;
}
.widget-user .box-footer {
    padding-top: 30px;
}
.widget-user .widget-user-header {
    padding: 20px;
    width: 386px;
    height: 120px;
    border-top-right-radius: 3px;
    border-top-left-radius: 3px;
}
.bg-black {
    background-color: #00a7d0 !important;
    color: #fff !important;
}
.row{
  width: 100%;
  display: table;
}
.description-text{
  font: 14px;
}
</style>

<script>
export default {
  mounted() {
    console.log("mounted");
  },
};
</script>
