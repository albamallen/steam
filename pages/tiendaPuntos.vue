<template>
    <title>TiendaPuntos</title>
    <div class="flex flex-col relative">
    <DropdownModal @click="dropdownModal()" v-if="dropdown" class="w-screen h-screen sticky top-0 left-0 z-50"></DropdownModal>

    <NavBar :shop="true" :primary="'puntos'" class="sticky top-0 z-20"></NavBar>
    <div class="flex p-11 gap-8">
        <p class="text-primary">MIS PUNTOS</p>
        <p>200</p>
    </div>
  <div class="flex flex-col gap-24">
    <div class="flex px-11 overflow-x-scroll  scrollbar gap-2.5">
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes>
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes> 
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes> 
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes> 
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes> 
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes> 
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes>
        
    </div>
    <div class="flex px-11 overflow-x-scroll  scrollbar gap-2.5">
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes>
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes> 
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes> 
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes> 
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes> 
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes> 
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes>
        
    </div> 
    <div class="flex px-11 overflow-x-scroll  scrollbar gap-2.5">
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes>
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes> 
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes> 
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes> 
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes> 
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes> 
        <CardJuegoMes :color="'dark'" :name="'Nombre del juegasso'" :img="'sampleimg.jpg'" >
                Establece y expande tus propios asentamientos, libera la tierra y ayuda a sus aldeanos. Recluta a otros para tu causa mientras aprendes más sobre la vida que tuviste que dejar atrás. Dirige a tus fuerzas, demuestra tu valor en el combate y consolida tu lugar como el héroe de tu pueblo.
        </CardJuegoMes>
        
    </div>
  </div>
    
    <!--<Footer></Footer>-->

</div>
</template>


<script setup>
let dropdown = ref(true)
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