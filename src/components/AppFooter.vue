<script>
export default {
    name: 'AppFooter',
    props: {
        post: Object,
    },
    data() {
        return {}
    },
    components: {},
};
</script>

<template>
  <!-- footer top -->
  <footer>
    <section style="background-color: black; padding: 100px;">
    <div class="container">
      <div class="row justify-content-center align-items-center g-2">
        <div class="col-md-4 text-center">
          <img :src="post.logo" class="pb-4" alt="Logo" />
          <p class="pb-4 text-white">{{ post.description }}</p>
          <span>
            <i
              v-for="link in post.socialLinks"
              :class="['fa-brands custom-hover', link.icon, 'pe-2']"
              :style="{ color: link.color }"
            ></i>
          </span>
        </div>

        <div class="col-md-4 text-center text-white">
          <h3 class="pb-2">RECENT POSTS</h3>
          <h6 v-for="postTitle in post.recentPosts" >
            <i class="fa-solid fa-arrow-right pe-1"></i>{{ postTitle }}
          </h6>
        </div>

        <div class="col-md-4 text-center text-white">
          <h3 class="pb-5">CONTACT INFORMATION</h3>
          <p class="pb-4">{{ post.contactInfo.address }}</p>
          <h6>{{ post.contactInfo.mobile }}</h6>
          <h6>{{ post.contactInfo.email }}</h6>
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

/* hover */
.custom-hover:hover{
  transform: scale(1.1); 
}
</style>
