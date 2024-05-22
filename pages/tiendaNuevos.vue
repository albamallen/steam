<template class="flex flex-col">
    <title>TiendaNuevos</title>
    <!--<NavBar :shop="true" :primary="'nuevos'" class="sticky"></NavBar>-->
    <div class="flex w-[98vw] gap-[2%]">
        <section class="flex relative bgimage w-[48vw]">
            <CardJuegoDestacado :name="'El juegón'" class="absolute top-10 left-10">
                Juego elegido que mola que flipas compratelo o te arrepentiras toda tu vida, está de oferta o algo no se
                que significa exactamente esta card
            </CardJuegoDestacado>
        </section>
        <div class="flex flex-col py-11 px-22 gap-8">
            <div class="flex justify-between">
                <h3>Populares</h3>
                <h3 class="text-g500">Próximamente</h3>
            </div>
            <div class="scroll-container ">
                <div class="flex gap-10 overflow-x-scroll w-[46vw] scrollbar">

                    <CardJuego>Nombre de Juego 1</CardJuego>
                    <CardJuego>Nombre de Juego 2</CardJuego>
                    <CardJuego>Nombre de Juego 3</CardJuego>
                    <CardJuego>Nombre de Juego 4</CardJuego>
                    <CardJuego>Nombre de Juego 5</CardJuego>
                    <CardJuego>Nombre de Juego 6</CardJuego>

                </div>
            </div>
            <div class="scroll-container ">
                <div class="flex gap-10 overflow-x-scroll w-[46vw] scrollbar">

                    <CardJuego>Nombre de Juego 1</CardJuego>
                    <CardJuego>Nombre de Juego 2</CardJuego>
                    <CardJuego>Nombre de Juego 3</CardJuego>
                    <CardJuego>Nombre de Juego 4</CardJuego>
                    <CardJuego>Nombre de Juego 5</CardJuego>
                    <CardJuego>Nombre de Juego 6</CardJuego>

                </div>
            </div>
        </div>
    </div>
   <!-- <Footer></Footer>-->

</template>


<script setup>

</script>


<style lang="sass" scoped>

 .bgimage
    background-image: url('sampleimg.jpg')
    background-size: cover
    background-position: center

.scrollbar
    scrollbar-width: thin
    scrollbar-color: black white

</style>