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
                    <span style="background-color:#ee1e29"><a href="#" class="text-white pe-2"><i
                                class="fa-brands fa-youtube px-2"></i>Youtube</a></span>
                </div>
                <div class="d-flex">
                    <span class="text-gray pt-0"
                        style="margin-top:25px;background-color: #cdcbcf;padding:1px 5px;border-color:#555454"><a href="#"
                            class="text-decoration-none text-secondary">999+</a></span>
                </div>
            </div>

            <p class="mb-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Et suscipit, repudiandae modi<br>
                temporibus ut, deleniti aliquam obcaecati totam fuga neque molestias harum qui! </p>

            <button class="btn-youtube-2 text-white"><i class="fa-brands fa-youtube pe-2"></i>Visit my
                Youtube channel</button>
        </div>
    </div>

    <!-- playlist -->
    <div class="container" style="margin-top: 100px;padding-bottom: 100px;">
        <div class="d-flex justify-content-between mb-4">
            <h4>Featured playlists</h4>
            <h6 class="pe-5"><b>View all videos <i class="fa-solid fa-greater-than fa-2xs ps-1 pt-2"></i> </b></h6>
        </div>

        <div class="d-flex justify-content-center">
            <div>
                <img src="../assets/img/video2-2x.jpg" style="width: 92%;">
                <h5 class="text-center pt-4">Thighs & glute workout</h5>
                <h6 class="text-center text-primary">Increase your mobility</h6>
            </div>
            <div>
                <img src="../assets/img/video7-2x.jpg" style="width: 92%;">
                <h5 class="text-center pt-4">Lift,firm & perk up</h5>
                <h6 class="text-center text-primary">Feel young again</h6>
            </div>
            <div>
                <img src="../assets/img/video9-2x.jpg" style="width: 92%;">
                <h5 class="text-center pt-4">Slim & trim your waist</h5>
                <h6 class="text-center text-primary">Shed these extra pounds</h6>
            </div>
        </div>
    </div>

    <!-- newsletter -->
    <section style="height: 500px;">
        <div class="container-fluid bg-image-newsletter" style="padding-bottom:100px;">
            <div class="container">
                <div>
                    <h5 class="text-danger" style="padding-top:100px;">Join our mailing list today</h5>
                    <h1 class="text-white" style="padding-bottom:100px;">Insider offers & flash sales in your <br> inbox
                        every week</h1>

                    <input type="email" placeholder="Insert your email..." class="input-newsletter">
                    <span><button class="btn-newsletter text-white">Suscribe</button></span>
                    <p class="pt-4">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eveniet saepe harum distinctio
                        <br>
                        nulla, quae, minima nostrum delectus.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- services card pt2 -->
    <section style="padding-top:150px;background-color: #060607;padding-bottom:100px;">
        <div class="container d-flex justify-content-center">
            <!-- 1 card -->
            <div class="card border-primary me-5" style="width: 24rem;border-width: 4px;background-color: #060607;">
                <div class="card-body text-center pb-5 pt-4">
                    <div class="pt-5 pb-2">
                        <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" fill="white" class="bi bi-smartwatch"
                            viewBox="0 0 16 16">
                            <path d="M9 5a.5.5 0 0 0-1 0v3H6a.5.5 0 0 0 0 1h2.5a.5.5 0 0 0 .5-.5V5z" />
                            <path
                                d="M4 1.667v.383A2.5 2.5 0 0 0 2 4.5v7a2.5 2.5 0 0 0 2 2.45v.383C4 15.253 4.746 16 5.667 16h4.666c.92 0 1.667-.746 1.667-1.667v-.383a2.5 2.5 0 0 0 2-2.45V8h.5a.5.5 0 0 0 .5-.5v-2a.5.5 0 0 0-.5-.5H14v-.5a2.5 2.5 0 0 0-2-2.45v-.383C12 .747 11.254 0 10.333 0H5.667C4.747 0 4 .746 4 1.667zM4.5 3h7A1.5 1.5 0 0 1 13 4.5v7a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 3 11.5v-7A1.5 1.5 0 0 1 4.5 3z" />
                        </svg>
                    </div>
                    <h4 class="card-title text-white mt-3">Team Training</h4>
                    <h5 class="card-subtitle mb-4 text-warning">Find a partner</h5>
                    <p class="card-text mb-3 text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde
                        quam quidem
                        repellat? Beatae temporibus.</p>
                    <a href="#" class="card-link text-decoration-none text-white">Find a partner <i
                            class="fa-solid fa-greater-than fa-2xs ps-1"></i></a>

                </div>
            </div>
            <!-- 2 card -->
            <div class="card border-primary me-5 ms-5" style="width: 24rem;border-width: 4px;background-color: #060607;">
                <div class="card-body text-center pb-5 pt-4">
                    <div class="pt-5 pb-2">
                        <i class="fa-solid fa-dumbbell fa-2xl text-white"></i>
                    </div>
                    <h4 class="card-title text-white mt-3">Crossfit workout</h4>
                    <h5 class="card-subtitle mb-4 text-warning">Push your limits</h5>
                    <p class="card-text mb-3 text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde
                        quam quidem
                        repellat? Beatae temporibus.</p>
                    <a href="#" class="card-link text-decoration-none text-white">Learn about Crossfit <i
                            class="fa-solid fa-greater-than fa-2xs ps-1"></i></a>

                </div>
            </div>
            <!-- 3 card -->
            <div class="card border-primary ms-5" style="width: 24rem;border-width: 4px;background-color: #060607;">
                <div class="card-body text-center pb-5 pt-4">
                    <div class="pt-5 pb-2">
                        <i class="fa-solid fa-weight-scale fa-2xl text-white"></i>
                    </div>
                    <h4 class="card-title text-white mt-3">Weight loss plan</h4>
                    <h5 class="card-subtitle mb-4 text-warning">Shed those pounds</h5>
                    <p class="card-text mb-3 text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde
                        quam quidem
                        repellat? Beatae temporibus.</p>
                    <a href="#" class="card-link text-decoration-none text-white">Schedule a workout
                        <i class="fa-solid fa-greater-than fa-2xs ps-1"></i></a>

                </div>
            </div>

        </div>
    </section>


    <!-- latest articles -->

    <section>
      

        <div class="container" style="padding: 100px;">
        <div class="d-flex justify-content-between mb-4">
            <h4 class="pe-4">Latest articles</h4>
            <h6 class="pe-5"><b>Read all articles <i class="fa-solid fa-greater-than fa-2xs ps-1 pt-2"></i> </b></h6>
        </div>

        <div class="d-flex justify-content-center">
            <div class="me-5">
                <img src="../assets/img/blog4-2x-1200x773.jpg" style="width:24rem;">
                <h5 class="text-center pt-4">The best protein shake</h5>
                <p class="text-center text-secondary">By <span class="text-black">Admin</span> | November 26th,2019 | <span class="text-black">Gym</span></p>
            </div>
            <div class="me-5"> 
                <img src="../assets/img/blog1-2x-1200x773.jpg" style="width:24rem;">
                <h5 class="text-center pt-4">Ultimate cardio workout</h5>
                <p class="text-center text-secondary">By <span class="text-black">Admin</span> | November 26th,2019 | <span class="text-black">Gym</span></p>
            </div>
            <div class="me-5">
                <img src="../assets/img/blog3-2x-1200x773.jpg" style="width:24rem;">
                <h5 class="text-center pt-4">New juices available now</h5>
                <p class="text-center text-secondary">By <span class="text-black">Admin</span> | November 26th,2019 | <span class="text-black">Gym</span></p>
            </div>
        </div>
    </div>
    </section>

    <!-- quotation -->
    <section class="img-custom-quotation d-flex align-items-center" style="padding: 100px; height: 700px;">
     <div class="container-fluid">
        <div class="container">
            <div class="text-center">
                <h1 class="text-white pb-5">"I've failed over and over again in my <br>
                    life. And that is why I succeed."</h1>

                <p class="text-white pb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex voluptate, reprehenderit, impedit consequatur ullam voluptatem ipsum <br>
                    alias exercitationem error dolores asperiores modi.</p>
                <button class="btn-custom-quotation text-white">Buy Avada today <i class="fa-solid fa-greater-than fa-2xs ps-1 pt-2"></i></button>
            </div>
        </div>
     </div>
</section>


<!-- 4 sport center -->
<section style="padding: 100px;">
<div class="container d-flex justify-content-center">
      <!-- card 1 -->
    <div class="card me-5 ms-5 border-0" style="width: 26rem;">
                <div class="card-body text-center pb-5 pt-4 ">
                    <div class="pt-5 pb-2">
                        <img src="../assets/img/sponsor-1-2x.png" class="w-100">
                    </div>
                    
                    <p class="card-text mb-3 text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde
                        quam quidem
                        repellat? Beatae temporibus.</p>
                    <a href="#" class="card-link text-decoration-none text-black">Visit Yoga Studio <i
                            class="fa-solid fa-greater-than fa-2xs ps-1"></i></a>

                </div>
            </div>

            <!-- card 2 -->
            <div class="card me-5 ms-5 border-0" style="width: 26rem;">
                <div class="card-body text-center pb-5 pt-4">
                    <div class="pt-5 pb-2">
                        <img src="../assets/img/sponsor-2-2x.png" class="w-100">
                    </div>
                    
                    <p class="card-text mb-3 text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde
                        quam quidem
                        repellat? Beatae temporibus.</p>
                    <a href="#" class="card-link text-decoration-none text-black">Visit Yoga Studio <i
                            class="fa-solid fa-greater-than fa-2xs ps-1"></i></a>

                </div>
            </div>

            <!-- card 3 -->
            <div class="card me-5 ms-5 border-0" style="width: 26rem;">
                <div class="card-body text-center pb-5 pt-4">
                    <div class="pt-5 pb-2">
                        <img src="../assets/img/sponsor-3-2x.png" class="w-100">
                    </div>
                    
                    <p class="card-text mb-3 text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde
                        quam quidem
                        repellat? Beatae temporibus.</p>
                    <a href="#" class="card-link text-decoration-none text-black">Visit Yoga Studio <i
                            class="fa-solid fa-greater-than fa-2xs ps-1"></i></a>

                </div>
            </div>

            <!-- card 4 -->
            <div class="card me-5 ms-5 border-0" style="width: 26rem;">
                <div class="card-body text-center pb-5 pt-4">
                    <div class="pt-5 pb-2">
                        <img src="../assets/img/sponsor-4-2x.png" class="w-100">
                    </div>
                    
                    <p class="card-text mb-3 text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde
                        quam quidem
                        repellat? Beatae temporibus.</p>
                    <a href="#" class="card-link text-decoration-none text-black">Visit Yoga Studio <i
                            class="fa-solid fa-greater-than fa-2xs ps-1"></i></a>

                </div>
            </div>


</div>
</section>



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
    object-fit: scale-down;
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

.btn-youtube-2 {
    background-color: red;
    border-radius: 20px;
    padding: 10px 25px;
    border-color: red;
}

/*fine youtube channel section */

/* newsletter section */
.bg-image-newsletter {
    background-image: url("../assets/img/banner1-2x.jpg");
    background-size: cover;
}

.input-newsletter {
    border-radius: 20px;
    padding: 6px 10px;
    width: 450px;
}

.btn-newsletter {
    padding: 8px 60px;
    border-radius: 20px;
    margin-left: 15px;
    border-color: $medium-blue;
    background-color: $medium-blue;
}

/* quotation section */
.img-custom-quotation{
background-image: url('../assets/img/banner2-2x.jpg');
background-size: cover;
}
.btn-custom-quotation{
    border-radius: 20px;
    padding:8px 20px;
    border-color: $medium-blue;
    background-color: $medium-blue;

}
/* fine quotation section */





</style>
