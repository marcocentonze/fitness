<script >

export default {
    name: 'AppFooter',
    data() {
        return {

        }
    },
    components: {

    },
};


</script>

<template>
  <!-- footer top -->
  <footer>
    <section style="background-color: black;padding:100px;">
    <div class="container">
       <div class="row justify-content-center align-items-center g-2">
        <div class="col-md-4 text-center">
            <img src="../assets/img/logo-200x34.png" class="pb-4">
            <p class="pb-4 text-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam nisi ratione nemo non, veritatis delectus cumque modi esse animi quas.</p>
            <span>
                <i class="fa-brands fa-facebook pe-2" style="color:#FF414B;"></i>
                <i class="fa-brands fa-twitter pe-2" style="color:#FF414B;"></i>
                <i class="fa-brands fa-youtube pe-2" style="color:#FF414B;"></i>
                <i class="fa-brands fa-instagram pe-2" style="color:#FF414B;"></i>
                <i class="fa-brands fa-linkedin pe-2" style="color:#FF414B;"></i>
            </span>
        </div>


        <div class="col-md-4 text-center text-white">
            <h3 class="pb-2">RECENT POSTS</h3>
            <h6 class=""><i class="fa-solid fa-arrow-right pe-1"></i>The best protein shake</h6>
            <h6><i class="fa-solid fa-arrow-right pe-1"></i>Ultimate cardio workout</h6>
            <h6 class="p-2"><i class="fa-solid fa-arrow-right pe-1"></i>New juices available now</h6>
            <h6><i class="fa-solid fa-arrow-right pe-1"></i>Tips to find training partners</h6>
            <h6 class="pt-2"><i class="fa-solid fa-arrow-right pe-1"></i>20 best healthy recipes</h6>
        </div>

        <div class="col-md-4 text-center text-white">
          <h3 class="pb-5">CONTACT INFORMATION</h3>
          <p class="pb-4">4746 Tipple Road Michigan 48449</p>
          <h6>Mobile : 1.800.000.0000</h6>
          <h6>Email: info@your-company.com</h6>
        </div>
       </div>
    </div>
</section>

<!-- footer bottom -->
<section style="height: 60px;background-color: black;">
   <div class="orizzontal-line-footer"></div>
    <p class="text-center text-secondary">© Copyright 2012 - 2020 | Avada theme by <span class="text-white">ThemeFusion</span> | All rights reserved | Powered by <span class="text-white">Wordpress</span></p>
</section>


    
  </footer>

</template>

<style lang="scss" scoped>
@use '../../src/assets/scss/variables' as *;

.orizzontal-line-footer{
    width:100%;
    border-top:2px solid $medium-grey;
    padding-bottom:20px;
}


</style>
