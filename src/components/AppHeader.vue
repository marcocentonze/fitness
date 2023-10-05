<script >

export default {
  name: 'AppHeader',
  props: {
        menu: Object
    },
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
    <div class="container bg-black d-flex align-items-center" style="height: 80px;">
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
      <div class="container-header-right d-flex justify-content-center">
        <div class="d-flex">
          <ul class="nav nav-underline">
        <li class="nav-item" v-for="item in menu">
          <a class="nav-link text-white" :href="item.url">{{ item.name }}</a>
        </li>
      </ul>
          
        </div>

        <div>
          <a class="text-black bg-btn-yellow text-decoration-none px-1 py-1 me-2">new</a>
          <button class="text-white bg-btn-blue ms-5">Schedule a workout</button>
          <i class="fa-solid fa-cart-shopping ms-5" style="color: grey;"></i>
          <i class="fa-solid fa-magnifying-glass ms-4" style="color: grey;"></i>
        </div>

      </div>
    </div>




  </div>
</template>

<style lang="scss"  scoped>
@use '../../src/assets/scss/variables' as *;
.container-header-left {
  width: 30%;
  background-color: black;
}

.container-header-right {
  width: 70%;
}

.text-header{
  color:#5F5B5F;
}
.bg-btn-yellow{
  background-color: $light-yellow;
  border-radius: 2px;
}
.bg-btn-blue{
  background-color: $medium-blue;
  border-radius: 20px;
  padding:5px 15px;
  border-color: $medium-blue;
}
</style>
