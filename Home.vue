<template>
  <div class="mt-3 rounded-3">
    <!-- card start -->
    <div class="card border-0">
      <div class="row">
        <!-- start card content -->
        <div class="col-lg-5 col-md-6">
          <div id="card-img">
            <img src="../support/Imgs/Gozalshop.jpg" alt="گوزل شاپ" class="card-img img-fluid">
          </div>
        </div>
        <div class="col-lg-7 col-md-6 mt-md-5">
          <div class="card-body" id="card-headerText">
            <h4 class="card-title">به فروشگاه ما خوش آمدید</h4>
            <h5 class="card-subtitle blockquote-footer mt-2 mb-2">به مدیریت زاده هاشم</h5>
            <p class="card-text" id="welcome-text">
              تضمین بهترین کیقیت با کمترین قیمت و همچنین تلاش ما بر مبنای جلب رضایت شما
              مشتریان عزیز و حفظ اعتماد شما می باشد !
            </p>
            <button class="btn btn-primary float-start mt-md-3">درباره ما</button>
          </div>
        </div>
      </div>
      <!-- end card content -->
    </div>
    <!-- end card -->
    <hr class="mt-5" />
    <!-- little description -->
    <div class="d-flex justify-content-center">
      <div id="icon-pagequality" class="ms-3"><i class="fa-solid fa-hand-peace"></i> کمترین قیمت</div>
      <div id="icon-pagerange"><i class="fa-solid fa-heart"></i> بیشترین کیفیت</div>
    </div>
    <hr />
    <!-- shop items card -->
    <div>
      <div class="row">
        <!-- two card -->
        <div class="col-md-6 col-12" id="card-one">
          <!-- start card -->
          <div class="card border-0">
            <div>
              <!-- card img -->
              <img src="../support/Imgs/Shop.jpg" alt="بهداشتی" class="card-img" />
            </div>
            <!-- card content -->
            <div class="card-body">
              <h6 class="card-title">کالا های بهداشتی</h6>
              <p class="card-text">
                در واقع ما بهترین کالا های بهداشتی شوینده را در اختیار شما میگذاریم تا
                بدون نگرانی از قیمت آن به خرید بپردازید.
              </p>
              <button class="btn btn-primary float-start">
                <router-link to="/بهداشتی" class="text-decoration-none text-white">
                  <i class="fa-solid fa-cart-shopping ms-1"></i> خرید
                </router-link>
              </button>
            </div>
          </div>
          <!-- end card -->
        </div>
        <div class="col-md-6 mt-md-0 mt-3 col-12" id="card-two">
          <!-- start card -->
          <div class="card border-0">
            <div>
              <!-- card img -->
              <img src="../support/Imgs/Shop2.jpg" alt="آرایشی" class="card-img" />
            </div>
            <!-- card content -->
            <div class="card-body">
              <h6 class="card-title">کالا های آرایشی</h6>
              <p class="card-text">
                و اما کالای بسیار پر طرفدار در ایران. چه کسی میتونه این لوازم آرایشی رو با
                این قیمت و کیفیت رد کنه؟
              </p>
              <button class="btn btn-primary float-start">
                <router-link to="/آرایشی" class="text-decoration-none text-white">
                  <i class="fa-solid fa-cart-shopping ms-1"></i> خرید
                </router-link>
              </button>
            </div>
          </div>
          <!-- end card -->
        </div>
        <!-- end card col -->
      </div>
      <!-- end shop items -->
    </div>
  </div>
</template>
<script>
export default {
  name: "page-home",
};
</script>
<style scoped>
@media screen and (min-width: 900px) {
  #card-headerText {

    margin-top: 100px;

  }

  /* welcome text */
  #welcome-text {
    transition: all 0.3s;
  }

  #welcome-text:hover {
    font-size: 20px;
  }

  /* cards */
  #card-one,
  #card-two {
    transition: all 0.3s;
  }

  #card-one:hover {
    transform: scale(1.05);
  }

  #card-two:hover {
    transform: scale(1.05);
  }

  /* icons */
  #icon-pagequality:hover {
    padding-bottom: 10px;
    border-bottom: 2px solid #1E88E5;
  }

  #icon-pagerange:hover {
    padding-bottom: 10px;
    border-bottom: 2px solid #1E88E5;
  }
}

@media screen and (max-width: 900px) {

  /* welcome text */
  #welcome-text {
    transition: all 0.3s;
  }

  #welcome-text:hover {
    font-size: 20px;
  }

  #icon-pagequality:hover {
    padding-bottom: 10px;
    border-bottom: 2px solid #1E88E5;
  }

  #icon-pagerange:hover {
    padding-bottom: 10px;
    border-bottom: 2px solid #1E88E5;
  }
}
</style>
