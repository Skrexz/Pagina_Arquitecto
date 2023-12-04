<template>
    <div>
        <h1 class="text-center text-uppercase py-2 bg-light">Mantenimientos</h1>
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
    <div class="space-barXD"></div>
    <div class="d-flex presentation-imgs justify-content-center">
        <img class="mx-1" src="../assets/img/mantenimientos/2/mantenimiento2.1.png" alt="">
        <img src="../assets/img/mantenimientos/1/mantenimiento1.2.jpg" alt="">

    </div>

    <div class="bg-light px-5 contenedor-proyectos">
        <h2 class="text-uppercase text-center py-3 text-decoration-underline">proyectos</h2>
        <div class="d-flex flex-column align-items-center">

            <div class="proyecto bg-white row justify-content-center" style="overflow: hidden;">
                <div class="col-md-5 col-sm-12">
                    <img src="../assets/img/mantenimientos/2/mantenimiento2.1.png" class="w-100" alt="">
                </div>
                <div class="col-md-5 col-sm-12 py-3 border-black border-end border-bottom border-top">
                    <h3 style="color: var(--main-green);" class="text-uppercase text-center">
                        MANTENIMIENTO INDUSTRIAL
                    </h3>
                    <hr>
                    <div class="d-flex align-content-center" style="height: 100%;">
                        <p class="text-center" style="font-size: 1.3rem;">Lorem ipsum, dolor sit amet consectetur
                            adipisicing elit. Sapiente voluptatem
                            illum, atque soluta similique eligendi suscipit quod laboriosam ipsam magnam, aut earum magni
                            architecto dolor repudiandae corporis molestias quae quisquam voluptates voluptatum. Unde
                            architecto iste blanditiis qui. Natus impedit consequuntur vel consequatur sit quidem? Velit
                            officia facilis iste illo officiis.</p>
                    </div>
                </div>
            </div>
            <div class="space-bar"></div>

            <div class="proyecto bg-white row justify-content-center" style="overflow: hidden;">
                <div class="col-md-5 col-sm-12 py-3 border-black border-start border-bottom border-top">
                    <h3 style="color: var(--main-green);" class="text-uppercase text-center">
                        MANTENIMIENTO DE FACHADA
                    </h3>
                    <hr>
                    <div class="d-flex align-content-center " style="height: 100%;">
                        <p class="text-center" style="font-size: 1.7rem;"><br>Mantenimiento y restauración de fachadas en vidrio, 
                            concreto, fachaletas en ladrillo y todo tipo de acabado cumpliendo con rigurosos estándares de 
                            limpieza y preservación
                            <br>
                            <br>
                            Nivel nacional</p>
                    </div>
                </div>
                <div class="col-md-5 col-sm-12">
                    <img src="../assets/img/mantenimientos/1/mantenimiento1.1.jpeg" class="w-100" alt="">
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
    background: url('../assets/img/mantenimientos/1/mantenimiento1.1.jpeg');
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
        margin: 0 1rem;
        width: 25vw ;
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

.space-barXD {
    height: 1.5rem;
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
}
</style>