<template>
    <main>
        <div class="row p-0 m-0 px-1 bg-dark text-white">
            <div class="col-md-4 col-sm-12 py-4 text-center">
                <h2 class="text-uppercase mision">Misión</h2>
                <p>INGSOLPRO se proyecta como un referente inigualable en la industria de
                     la construcción especializada en estructuras metálicas, instalación de cubiertas, diseño e instalación 
                     de fachadas arquitectónicas y mantenimiento de infraestructura. Nos visualizamos como líderes innovadores, 
                     impulsando el progreso con soluciones de vanguardia que establecen nuevos estándares en durabilidad, eficiencia 
                     y sostenibilidad.</p>
            </div>
            <div class="col-md-4 col-sm-12 ">
                <img src="../assets/img/LogoSubtitulos.png" alt="" class="img-fluid">
            </div>
            <div class="col-md-4 col-sm-12  py-4 text-center">
                <h2 class="text-uppercase vision">visión</h2>
                <p>En Ingsolpro, nos dedicamos a ofrecer servicios de ejecución y supervisión de obras civiles con los más altos
                     estándares de calidad y profesionalismo. Nuestra misión es satisfacer las necesidades de nuestros clientes
                      mediante la entrega puntual de proyectos de construcción seguros y eficientes. Valoramos a nuestros empleados 
                      como el recurso más valioso de la empresa, fomentando un entorno laboral colaborativo y orientado al crecimiento
                       profesional.</p>
            </div>
        </div>

        <section class="text-center d-flex align-items-center justify-content-center quienes-somos px-1 py-5 flex-column">
            <div class="back-ground"></div>
            <img src="../assets/img/quienessomos.jpg" alt="">
            <h1 class="mb-2 text-white">¿Quiénes somos?</h1>
            <p class="w-50 text-white">Somos más que una empresa de construcción; somos INGSOLPRO, un equipo apasionado de profesionales
                 comprometidos con la ingeniería de vanguardia y soluciones integrales. Con sede en Santander, Colombia, nos enorgullece
                  ser un actor clave en el desarrollo de infraestructuras que definen el paisaje arquitectónico de la región.</p>
        </section>

        <section>
            <div class="d-flex justify-content-around flex-wrap people-container">
                <div class="back-ground-yellow"></div>
                <div class="people bg-dark">
                    <img src="../assets/img/image4.jpg" alt="" class="img-fluid">
                    <h2 class="text-white text-center ">Juan Sebastian Bautista</h2>
                    <p class="text-white text-center">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Corporis
                        quasi
                        quia blanditiis exercitationem ullam est? Deleniti mollitia facere voluptatem tempore, rem
                        explicabo!
                        Voluptates laudantium excepturi iure modi consequuntur doloremque earum culpa numquam dolorem
                        aperiam
                        illo aliquid nesciunt eum explicabo, tenetur aut nobis rerum possimus ut alias asperiores quaerat
                        obcaecati? Sequi delectus architecto earum, possimus praesentium deserunt ad dolores dicta aut
                        cupiditate quidem expedita porro asperiores consectetur? Qui at temporibus velit corporis culpa,
                        repudiandae vitae quisquam optio nam voluptatibus reprehenderit officia?</p>

                </div>

                <div class="people bg-dark">
                    <img src="../assets/img/image4.jpg" alt="" class="img-fluid">
                    <h2 class="text-white text-center ">Juan Camilo Rangel</h2>
                    <p class="text-white text-center">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Corporis
                        quasi
                        quia blanditiis exercitationem ullam est? Deleniti mollitia facere voluptatem tempore, rem
                        explicabo!
                        Voluptates laudantium excepturi iure modi consequuntur doloremque earum culpa numquam dolorem
                        aperiam
                        illo aliquid nesciunt eum explicabo, tenetur aut nobis rerum possimus ut alias asperiores quaerat
                        obcaecati? Sequi delectus architecto earum, possimus praesentium deserunt ad dolores dicta aut
                        cupiditate quidem expedita porro asperiores consectetur? Qui at temporibus velit corporis culpa,
                        repudiandae vitae quisquam optio nam voluptatibus reprehenderit officia?</p>

                </div>

                <div class="people bg-dark">
                    <img src="../assets/img/image4.jpg" alt="" class="img-fluid">
                    <h2 class="text-white text-center ">Laura Lopez</h2>
                    <p class="text-white text-center">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Corporis
                        quasi
                        quia blanditiis exercitationem ullam est? Deleniti mollitia facere voluptatem tempore, rem
                        explicabo!
                        Voluptates laudantium excepturi iure modi consequuntur doloremque earum culpa numquam dolorem
                        aperiam
                        illo aliquid nesciunt eum explicabo, tenetur aut nobis rerum possimus ut alias asperiores quaerat
                        obcaecati? Sequi delectus architecto earum, possimus praesentium deserunt ad dolores dicta aut
                        cupiditate quidem expedita porro asperiores consectetur? Qui at temporibus velit corporis culpa,
                        repudiandae vitae quisquam optio nam voluptatibus reprehenderit officia?</p>

                </div>

                <div class="people bg-dark">
                    <img src="../assets/img/image4.jpg" alt="" class="img-fluid">
                    <h2 class="text-white text-center ">Luis Carlos Santos</h2>
                    <p class="text-white text-center">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Corporis
                        quasi
                        quia blanditiis exercitationem ullam est? Deleniti mollitia facere voluptatem tempore, rem
                        explicabo!
                        Voluptates laudantium excepturi iure modi consequuntur doloremque earum culpa numquam dolorem
                        aperiam
                        illo aliquid nesciunt eum explicabo, tenetur aut nobis rerum possimus ut alias asperiores quaerat
                        obcaecati? Sequi delectus architecto earum, possimus praesentium deserunt ad dolores dicta aut
                        cupiditate quidem expedita porro asperiores consectetur? Qui at temporibus velit corporis culpa,
                        repudiandae vitae quisquam optio nam voluptatibus reprehenderit officia?</p>

                </div>

                

            </div>
        </section>

        <MyFooter></MyFooter>

    </main>
</template>

<script setup>
import MyFooter from '../components/shared/MyFooter.vue';
import { Icon } from '@iconify/vue';

</script>

<style lang="scss" scoped>
.quienes-somos {
    overflow: hidden;
    position: relative;
    height: 65vh;

    img {
        height: 150px;
    }

    .back-ground {
        position: absolute;
        background: var(--main-green);
        transform: rotate(-10deg);
        z-index: -1;
        width: 200%;
        height: 130%;
    }
}

.personas {
    img {
        max-width: 25%;
    }
}

.mision,
.vision {
    text-shadow: 3px 3px 1px rgb(197, 197, 197);
}

img:hover {
    transition: all .3s;
    transform: scale(1.05);
}

.people-container{
    position: relative;
    overflow: hidden;
    .back-ground-yellow{
        position: absolute;
        background: #b39e09;
        transform: rotate(10deg);
        z-index: -1;
        width: 200%;
        height: 80%;
    }
    .people{
    width: 27%;
    margin: 1%;
    h2{
        margin: 1rem 0;
    }
    p{
        padding: 0 .5rem ;
    }
    border-radius: 5px;
    margin-bottom: 1rem;
}
}


@media (max-width: 992px) {
    .quienes-somos {
        p {
            width: 100% !important;
        }
    }

    .personas {
        flex-wrap: wrap;

        img {
            width: 100%;
            max-width: none;
        }

        .info-lideres {
            padding: 1rem 0;
        }
    }


    .people{
    width: 100% !important;
}
}


</style>