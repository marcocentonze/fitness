<script >

export default {
  name: 'AppHeader',
  data() {
    return {

    }
  },
  components: {

  },
};


</script>

<template>
  <div class="container-fluid bg-black">
    <div class="container bg-black d-flex">
      <!-- left -->
      <div class="container-header-left">

        <nav class="navbar bg-black">
          <div class="container bg-black">
            <a class="navbar-brand" href="#">
              <img src="../assets/img/logo-200x34.png" alt="Bootstrap">
            </a>
          </div>
        </nav>
      </div>

      <!-- right -->
      <div class="container-header-right d-flex">
        <div class="d-flex">
          <ul class="nav nav-underline">
            <li class="nav-item">
              <a class="nav-link text-white" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white" href="#">Services</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white" href="#">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white">Videos</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white">Blog</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white">Store</a>
            </li>
          </ul>
          <button class="text-white">New</button>
        </div>

        <div>
          <button class="text-white">Button</button>
          <i class="fa-solid fa-cart-shopping" style="color: grey;"></i>
          <i class="fa-solid fa-magnifying-glass" style="color: grey;"></i>
        </div>

      </div>
    </div>




  </div>
</template>

<style scoped>
.container-header-left {
  width: 30%;
  background-color: black;
}

.container-header-right {
  width: 70%;
}
</style>
