<template>
    <div>
        <h1 class="text-center text-uppercase py-2 bg-light">CUBIERTAS</h1>
    </div>

    <div class="banner">
        <div class="info d-flex align-items-center p-1">
            <p class="text-center text-white">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque atque ad quos quibusdam odio rerum accusamus
                consequuntur
                modi, ut vel mollitia voluptatem dolores vero, delectus minima praesentium quia illo quo.
            </p>
        </div>
    </div>

    <div class="row mt-3">
        <div class="col-md-4 col-sm-12 py-3 d-flex flex-column justify-content-center">
            <h2 class="text-center ">Mantenimiento
                relativamente bajo
            </h2>
            <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta ipsam quaerat totam
                tempora sint quas soluta nihil libero, sit consequuntur.</p>
        </div>
        <div class="col-md-4 col-sm-12" style="background: var(--main-green);">
            <img src="../assets/img/LogoSubtitulos.png" alt="" class="w-100">
        </div>
        <div class="col-md-4 col-sm-12 py-3 d-flex flex-column justify-content-center">
            <h2 class="text-center ">Resistencia y durabilidad</h2>
            <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta ipsam quaerat totam
                tempora sint quas soluta nihil libero, sit consequuntur.</p>
        </div>
    </div>

    <div class="d-flex presentation-imgs justify-content-center">
        <img class="mx-4" src="../assets/img/cubiertas/1/cubiertas1.3.jpeg" alt="">
        <img src="../assets/img/cubiertas/2/cubiertas2.1.png" alt="">
    </div>

    <div class="bg-light px-5 contenedor-proyectos">
        <h2 class="text-uppercase text-center py-3 text-decoration-underline">proyectos</h2>
        <div class="d-flex flex-column align-items-center">

            <div class="proyecto bg-white row justify-content-center" style="overflow: hidden;">
                <div class="col-md-5 col-sm-12">
                    <img src="../assets/img/cubiertas/1/cubiertas1.3.jpeg" class="w-100" alt="">
                </div>
                <div class="col-md-5 col-sm-12 py-3 border-black border-end border-bottom border-top">
                    <h3 style="color: var(--main-green);" class="text-uppercase text-center">
                        Cubierta autoportante
                    </h3>
                    <hr>
                    <div class="d-flex align-content-center" style="height: 100%, border-radius 100px;">
                        <p class="text-center" style="font-size: 1.7rem;"><br>Fabricación e instalación de cubierta
                             autoportante tipo Steel-Roof para cubrir una luz de 18 metros aproximadamente perteneciente
                              a una cancha múltiple.
                              <br>
                              <br>
                            San Gil, Santander
                            <br>
                            2022</p>
                    </div>
                </div>
            </div>
            <div class="space-bar"></div>

            <div class="proyecto bg-white row justify-content-center" style="overflow: hidden;">
                <div class="col-md-5 col-sm-12 py-3 border-black border-start border-bottom border-top">
                    <h3 style="color: var(--main-green);" class="text-uppercase text-center">
                        Cubierta standig seam
                    </h3>
                    <hr>
                    <div class="d-flex align-content-center" style="height: 100%;">
                        <p class="text-center" style="font-size: 1.7rem;"><br>Instalación y modulación de cubierta
                             tipo Standing seam sin traslapo para un espacio público de 300 m2 aproximadamente
                             <br>
                             <br>
                            Piendamó, Cauca
                            <br>
                            2021</p>
                    </div>
                </div>
                <div class="col-md-5 col-sm-12">
                    <div id="carouselExampleIndicators" class="carousel slide">
                        <div class="carousel-indicators">
                            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0"
                                class="active" aria-current="true" aria-label="Slide 1"></button>
                            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
                                aria-label="Slide 2"></button>
                            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
                                aria-label="Slide 3"></button>
                        </div>
                        <div class="carousel-inner">
                            <div class="carousel-item active">
                                <img src="../assets/img/cubiertas/2/cubiertas2.1.png" class="d-block w-100"
                                alt="Slide 1">
                            </div>
                            <div class="carousel-item active">
                                <img src="../assets/img/cubiertas/1/cubiertas1.1.jpeg" class="d-block w-100"
                                alt="Slide 2">
                            </div>
                            <div class="carousel-item active">
                                <img src="../assets/img/cubiertas/1/cubiertas1.3.jpeg" class="d-block w-100"
                                alt="Slide 3">
                            </div>
                        </div>
                        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators"
                            data-bs-slide="prev">
                            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                            <span class="visually-hidden">Previous</span>
                        </button>
                        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators"
                            data-bs-slide="next">
                            <span class="carousel-control-next-icon" aria-hidden="true"></span>
                            <span class="visually-hidden">Next</span>
                        </button>
                    </div>
                </div>
            </div>
            <div class="space-bar"></div>

        </div>
    </div>

    <MyFooter></MyFooter>
</template>

<script setup>
import MyFooter from '../components/shared/MyFooter.vue';
</script>

<style lang="scss" scoped>
.banner {
    background: url('../assets/img/cubiertas/1/cubiertas1.1.jpeg');
    background-repeat: no-repeat;
    background-size: cover;
    height: 80vh;

    .info {
        background: rgba(0, 0, 0, 0.521);
        width: 30vw;
        height: 100%;
    }
}

.proyecto {
    img {
        height: 450px;
        object-fit: fill;
    }
}

.presentation-imgs {
    padding: 2rem 0;

    img {
        width: 25vw;
        transition: all 0.3s;
        object-fit: cover;

        &:hover {
            transform: scale(1.05);
        }
    }
}


.space-bar {
    height: 1.5rem;
    background: rgb(209, 209, 9);
    width: 25%;
}

@media (max-width: 992px) {
    .banner {
        background-position: 60%;

        .info {
            width: 100vw !important;
        }
    }


    .presentation-imgs {
        img {
            width: 100% !important;
        }
    }


    .proyecto {
        overflow: auto !important;
        margin: 1rem 0;

        img {
            height: 250px;
            order: 1;
        }
    }

    .space-bar {
        display: none;
    }

    .col-md-4 {
        order: 2;
    }

    .contenedor-proyectos {
        padding: 0 !important;
    }
}</style>