<template>
    <title>TiendaJuegos</title>
    <div class="flex flex-col relative">
    <DropdownModal @click="dropdownModal()" v-if="dropdown" class="w-screen h-screen sticky top-0 left-0 z-50"> </DropdownModal>

    <!---NavBar :shop="true" :primary="'ofertas'" class="sticky top-0 z-20"></NavBar>-->
    <div class="flex flex-col">
        <Dropdown @click="dropdownModal()"></Dropdown>
        <section class="flex relative bgimage w-[98vw] h-[70vh] rounded-3xl mb-11">
            <CardJuegoDestacado :name="'El juegón'" class="absolute top-10 left-10">
                Juego elegido que mola que flipas compratelo o te arrepentiras toda tu vida, está de oferta o algo no se
                que significa exactamente esta card
            </CardJuegoDestacado>
        </section>
        <div class="scroll-container ">
            <div class="flex gap-10 overflow-x-scroll scrollbar">

                <CardJuegoMes :color="'dark'" :name="'Nombre de Juego 1'" :img="'sampleimg.jpg'">
                    I have a dashboard with two sides, a nav on the left and the main content on the right, simple. They
                    both are housed by a main div which has the height of the current screen. I need the main content
                    div to scroll internally not scroll with the entire view when content overflows. All this while the
                    nav on the right remains as is without being affected by the content overflow on the main content
                    div
                </CardJuegoMes>
                <CardJuegoMes :color="'dark'" :name="'Nombre de Juego 2'" :img="'sampleimg.jpg'">
                    I have a dashboard with two sides, a nav on the left and the main content on the right, simple. They
                    both are housed by a main div which has the height of the current screen. I need the main content
                    div to scroll internally not scroll with the entire view when content overflows. All this while the
                    nav on the right remains as is without being affected by the content overflow on the main content
                    div
                </CardJuegoMes>
                <CardJuegoMes :color="'dark'" :name="'Nombre de Juego 3'" :img="'sampleimg.jpg'">
                    I have a dashboard with two sides, a nav on the left and the main content on the right, simple. They
                    both are housed by a main div which has the height of the current screen. I need the main content
                    div to scroll internally not scroll with the entire view when content overflows. All this while the
                    nav on the right remains as is without being affected by the content overflow on the main content
                    div
                </CardJuegoMes>
                <CardJuegoMes :color="'dark'" :name="'Nombre de Juego 4'" :img="'sampleimg.jpg'">
                    I have a dashboard with two sides, a nav on the left and the main content on the right, simple. They
                    both are housed by a main div which has the height of the current screen. I need the main content
                    div to scroll internally not scroll with the entire view when content overflows. All this while the
                    nav on the right remains as is without being affected by the content overflow on the main content
                    div
                </CardJuegoMes>
                <CardJuegoMes :color="'dark'" :name="'Nombre de Juego 5'" :img="'sampleimg.jpg'">
                    I have a dashboard with two sides, a nav on the left and the main content on the right, simple. They
                    both are housed by a main div which has the height of the current screen. I need the main content
                    div to scroll internally not scroll with the entire view when content overflows. All this while the
                    nav on the right remains as is without being affected by the content overflow on the main content
                    div
                </CardJuegoMes>
                <CardJuegoMes :color="'dark'" :name="'Nombre de Juego 6'" :img="'sampleimg.jpg'">
                    I have a dashboard with two sides, a nav on the left and the main content on the right, simple. They
                    both are housed by a main div which has the height of the current screen. I need the main content
                    div to scroll internally not scroll with the entire view when content overflows. All this while the
                    nav on the right remains as is without being affected by the content overflow on the main content
                    div
                </CardJuegoMes>

            </div>
        </div>
        <Dropdown @click="dropdownModal()"></Dropdown>
        <section class="flex relative bgimage w-[98vw] h-[70vh] rounded-3xl mb-11">
            <CardJuegoDestacado :name="'El juegón'" class="absolute top-10 left-10">
                Juego elegido que mola que flipas compratelo o te arrepentiras toda tu vida, está de oferta o algo no se
                que significa exactamente esta card
            </CardJuegoDestacado>
        </section>
        <div class="scroll-container ">
            <div class="flex gap-10 overflow-x-scroll scrollbar">

                <CardJuegoMes :color="'dark'" :name="'Nombre de Juego 1'" :img="'sampleimg.jpg'">
                    I have a dashboard with two sides, a nav on the left and the main content on the right, simple. They
                    both are housed by a main div which has the height of the current screen. I need the main content
                    div to scroll internally not scroll with the entire view when content overflows. All this while the
                    nav on the right remains as is without being affected by the content overflow on the main content
                    div
                </CardJuegoMes>
                <CardJuegoMes :color="'dark'" :name="'Nombre de Juego 2'" :img="'sampleimg.jpg'">
                    I have a dashboard with two sides, a nav on the left and the main content on the right, simple. They
                    both are housed by a main div which has the height of the current screen. I need the main content
                    div to scroll internally not scroll with the entire view when content overflows. All this while the
                    nav on the right remains as is without being affected by the content overflow on the main content
                    div
                </CardJuegoMes>
                <CardJuegoMes :color="'dark'" :name="'Nombre de Juego 3'" :img="'sampleimg.jpg'">
                    I have a dashboard with two sides, a nav on the left and the main content on the right, simple. They
                    both are housed by a main div which has the height of the current screen. I need the main content
                    div to scroll internally not scroll with the entire view when content overflows. All this while the
                    nav on the right remains as is without being affected by the content overflow on the main content
                    div
                </CardJuegoMes>
                <CardJuegoMes :color="'dark'" :name="'Nombre de Juego 4'" :img="'sampleimg.jpg'">
                    I have a dashboard with two sides, a nav on the left and the main content on the right, simple. They
                    both are housed by a main div which has the height of the current screen. I need the main content
                    div to scroll internally not scroll with the entire view when content overflows. All this while the
                    nav on the right remains as is without being affected by the content overflow on the main content
                    div
                </CardJuegoMes>
                <CardJuegoMes :color="'dark'" :name="'Nombre de Juego 5'" :img="'sampleimg.jpg'">
                    I have a dashboard with two sides, a nav on the left and the main content on the right, simple. They
                    both are housed by a main div which has the height of the current screen. I need the main content
                    div to scroll internally not scroll with the entire view when content overflows. All this while the
                    nav on the right remains as is without being affected by the content overflow on the main content
                    div
                </CardJuegoMes>
                <CardJuegoMes :color="'dark'" :name="'Nombre de Juego 6'" :img="'sampleimg.jpg'">
                    I have a dashboard with two sides, a nav on the left and the main content on the right, simple. They
                    both are housed by a main div which has the height of the current screen. I need the main content
                    div to scroll internally not scroll with the entire view when content overflows. All this while the
                    nav on the right remains as is without being affected by the content overflow on the main content
                    div
                </CardJuegoMes>

            </div>
        </div>
    </div>
    <!----<Footer></Footer>-->

</div>
</template>


<script setup>
import { ref } from 'vue';

let dropdown = ref(false)
const dropdownModal = () => {
   dropdown.value = !dropdown.value 
}

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