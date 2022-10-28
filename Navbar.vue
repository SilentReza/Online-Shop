<template>
  <div>
    <!-- start Navbar -->
    <div class="navbar navbar-expand-md navbar-dark bg-primary rounded-3">
      <!-- page brand -->
      <router-link to="/" class="navbar-brand ms-0">
        <i class="fa-solid fa-cart-shopping"></i> گوزل شاپ
      </router-link>
      <!-- btn for Phone users to use navbar -->
      <button class="btn navbar-toggler ms-2" data-bs-toggle="collapse" data-bs-target="#page-collapse">
        <i class="navbar-toggler-icon"></i>
      </button>
      <!-- start collapse -->
      <div class="collapse navbar-collapse mt-md-0 mt-3" id="page-collapse">
        <ul class="nav navbar-nav me-0">
          <!-- home item -->
          <li class="nav-item ms-md-2">
            <router-link class="nav-link" to="/">
              <i class="fa-solid fa-house"></i> خانه
            </router-link>
          </li>
          <!-- dropdown for shop item -->
          <div class="dropdown">
            <li class="nav-item ms-md-2">
              <router-link class="nav-link dropdown-toggle" to="#" data-bs-toggle="dropdown">
                <i class="fa-solid fa-shop"></i> فروشگاه
              </router-link>
              <ul class="dropdown-menu mt-2 text-end ms-md-0 ms-4">
                <!-- shop items -->
                <li>
                  <router-link class="dropdown-item" to="/آرایشی">
                    <i class="fa-solid fa-umbrella-beach ms-1"></i> آرایشی
                  </router-link>
                </li>
                <li>
                  <router-link class="dropdown-item" to="/بهداشتی">
                    <i class="fa-solid fa-hand-holding-droplet ms-1"></i> بهداشتی
                  </router-link>
                </li>
              </ul>
            </li>
          </div>
          <!-- about us item -->
          <li class="nav-item ms-md-2">
            <router-link class="nav-link" to="#">
              <i class="fa-solid fa-clipboard"></i> درباره
            </router-link>
          </li>
          <!-- connect us item -->
          <div class="dropdown">
            <li class="nav-item ms-md-2">
              <a class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#">
                <i class="fa-solid fa-paperclip"></i> ارتباط
              </a>
              <ul class="dropdown-menu mt-2 text-end ms-md-0 ms-4">
                <!-- connect items -->
                <li>
                  <a class="dropdown-item"
                    href="https://api.whatsapp.com/send/?phone=989148997526&text&type=phone_number&app_absent=0"
                    target="_blank">
                    <i class="fa fa-whatsapp ms-1"></i> واتساپ
                  </a>
                </li>
                <li>
                  <a class="dropdown-item" href="https://www.instagram.com/goozalshop/" target="_blank">
                    <i class="fa fa-instagram ms-1"></i> اینستاگرام
                  </a>
                </li>
                <!-- end content items -->
              </ul>
            </li>
            <!--end nav items -->
          </div>
        </ul>
      </div>
      <!-- end collapse -->
    </div>
    <!-- end navbar nav -->
  </div>
</template>

<script>
export default {
  name: "navbar-page",
};
</script>
<style scoped>

</style>
