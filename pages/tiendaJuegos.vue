<template class="flex flex-col">
    <title>TiendaJuegos</title>
    

    <DropdownModal @click="dropdownModal()" v-if="dropdown" class="w-screen h-screen sticky top-0 left-0 z-50"></DropdownModal>

    <div class="flex flex-col p-11 gap-11">
        <Dropdown @click="dropdownModal()"></Dropdown>
        <div class="flex gap-10 overflow-x-scroll  scrollbar">
            <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'">
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
            </CardJuegoMes>
            <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'">
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
            </CardJuegoMes>
            <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'">
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
            </CardJuegoMes>
            <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'">
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
            </CardJuegoMes>
            <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'">
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
            </CardJuegoMes>
            <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'">
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
            </CardJuegoMes>
            <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'">
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
            </CardJuegoMes>
            
        </div>
    </div>
     <!-- <Footer></Footer>-->

</template>


<script setup>

</script>


<style lang="sass" scoped>

//  .bgimage
//     background-image: url('sampleimg.jpg')
//     background-size: cover
//     background-position: center

.scrollbar
    scrollbar-width: thin
    scrollbar-color: black white

</style>