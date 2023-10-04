<script >

export default {
    name: 'AppMain',
    data() {
        return {

        }
    },
    components: {

    },
};


</script>

<template>
    <!-- take control of your health section -->
    <section class="take-control">
        <div class="container-fluid bg-image-custom">
            <div class="container">

                <div class="">
                    <!-- left -->
                    <h5 class="text-danger" style="padding-top:150px;">Certified fitness professional</h5>
                    <h1 class="display-2 text-white"><b>Take control of your health</b></h1>
                    <!-- linea gialla -->
                    <p style="color:#5F5B5F;">Curabitur non nulla sit amet nisl tempus convalids quis act lectus dolor sit
                        amet.</p>
                    <span>
                        <button class="btn-youtube text-white me-3"><i class="fa-brands fa-youtube pe-2"></i>Visit my
                            Youtube channel</button>
                        <button class="btn-buy-avada text-white">Buy Avada today <i
                                class="fa-solid fa-arrow-right"></i></button>
                    </span>
                </div>
            </div>
            <!-- right è l'immagine messo come bg -->

        </div>
    </section>


    <!-- services section -->
    <section class="services">

        <div class="container-fluid">
            <div class="container">
                <div class="d-flex">
                    <div class="img-services d-flex flex-column me-5" style="margin-top: -50px;">
                        <h3 class="text-white mt-auto ms-5">Crossfit workout</h3>
                        <h6 class="text-warning ms-5">Push your limits</h6>
                    </div>

                    <div class="img-services-2 d-flex flex-column me-5" style="margin-top: -50px;">
                        <h3 class="text-white mt-auto ms-5">New gym apparel</h3>
                        <h6 class="text-warning ms-5">Look good,feel good</h6>
                    </div>

                    <div class="img-services-3 d-flex flex-column" style="margin-top: -50px;">
                        <h3 class="text-white mt-auto ms-5">Team training</h3>
                        <h6 class="text-warning ms-5">Find a partner</h6>
                    </div>







                </div>

                <!-- review -->
                <div class="text-center mt-5 mb-5">
                    <h3>"How you respond to the challenge in the second half <br>
                        will determine what you become after the game,<br>
                        wether you are a winner or a loser."
                    </h3>
                </div>
                <div class="d-flex justify-content-center" style="padding-bottom:140px;">
                    <img class="avatar-services mx-2" src="../assets/img/avatar-1-2x.jpg">
                    <p class="text-white mx-2">Brad Johnson</p>
                    <p>Las Vegas</p>
                </div>


            </div>

        </div>

    </section>


    <!-- youtube playlist section -->
    <div class="container-fluid d-flex">
        <!-- img left -->
        <div style="width: 50%;margin-top:-60px;">
            <img src="../assets/img/service15-2x.jpg" class="img-youtube-custom">
        </div>

        <!-- text right -->
        <div style="width: 50%;">
            <h4 class="text-primary mb-4">Tune up your workouts</h4>
            <h1 class="display-3 mb-4">The best health & fitness<br> advice online</h1>


            <div class="d-flex mb-4">
                <img src="../assets/img/unnamed.jpg">
                <div class="info">
                    <a href="#" style="color:#888788">ThemeFusion</a>
                    <span style="background-color:#ee1e29"><a href="#" class="text-white pe-2"><i class="fa-brands fa-youtube px-2"></i>Youtube</a></span>
                </div>
                <div class="d-flex">
                    <span class="text-gray pt-0" style="margin-top:25px;background-color: #cdcbcf;padding:1px 5px;border-color:#555454"><a href="#" class="text-decoration-none text-secondary">999+</a></span>
                </div>
            </div>

            <p class="mb-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Et suscipit, repudiandae modi<br> temporibus ut, deleniti aliquam obcaecati totam fuga neque molestias harum qui! </p>

            <button class="btn-youtube-2 text-white"><i class="fa-brands fa-youtube pe-2"></i>Visit my
                            Youtube channel</button>
        </div>
        



    </div>
</template>

<style lang="scss" scoped>
@use '../../src/assets/scss/variables' as *;

/* section take control */
.bg-image-custom {
    background-image: url("../assets/img/slider82x-scaled.jpg");
    background-size: cover;
    height: 700px;
}


.btn-youtube {
    background-color: $medium-blue;
    border-radius: 20px;
    padding: 10px 25px;
    border-color: $medium-blue;
}

.btn-buy-avada {
    background-color: $dark-black;
    border-radius: 20px;
    padding: 10px 25px;
    border-color: $medium-grey;
}

/* fine section take control */



/* section services */
.services {
    background: rgb(9, 65, 214);
    background: linear-gradient(90deg, rgba(9, 65, 214, 1) 13%, rgba(204, 69, 252, 1) 34%, rgba(180, 58, 167, 1) 63%, rgba(252, 69, 91, 1) 98%);

    .img-services {
        background-image: url("../assets/img/service6-2x.jpg");
        background-size: cover;
        background-position: center center;
        width: 350px;
        aspect-ratio: 1/1;

    }

    .img-services-2 {
        background-image: url("../assets/img/box1-2x.jpg");
        background-size: cover;
        background-position: center center;
        width: 350px;
        aspect-ratio: 1/1;
    }

    .img-services-3 {
        background-image: url("../assets/img/box3-2x.jpg");
        background-size: cover;
        background-position: center center;
        width: 350px;
        aspect-ratio: 1/1;
    }


    .avatar-services {
        width: 30px;
        border-radius: 50%;
        object-fit: cover;
        object-position: right;

    }

}


/* fine section services */

/* youtube channel section */
.img-youtube-custom {
    width: 90%;
    object-fit:scale-down ;
    border-bottom-right-radius: 20px;
    border-top-right-radius: 2px;
}

.d-flex {
  display: flex;
  align-items: center; 
}

.info {
  display: flex;
  flex-direction: column; 
  margin-left: 10px;
}

.info a {
  text-decoration: none;
}

.fa-youtube {
  margin-right: 5px; 
}
.btn-youtube-2{
    background-color: red;
    border-radius: 20px;
    padding: 10px 25px;
    border-color: red;
}
/*fine youtube channel section */










</style>
