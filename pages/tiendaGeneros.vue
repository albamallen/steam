<template class="flex flex-col">
    <title>TiendaJuegos</title>
    <!--<NavBar :shop="true" :primary="'juegos'" class="sticky"></NavBar>-->
        <div class="flex flex-col">
            <Dropdown></Dropdown>
            <div class="flex flex-wrap gap-7 p-14 justify-center bg-g800">
                <CardGenero :img="''">Indie</CardGenero>
                <CardGenero :img="''">Rol</CardGenero>
                <CardGenero :img="''">Estrategia</CardGenero>
                <CardGenero :img="''">Aventura</CardGenero>
                <CardGenero :img="''">Arcade</CardGenero>
                <CardGenero :img="''">Storytelling</CardGenero>
            </div>
        </div>
        <div class="flex flex-col">
            <Dropdown></Dropdown>
            <div class="flex flex-wrap gap-7 p-14 justify-center bg-g800">
                <CardGenero :img="''">Individual</CardGenero>
                <CardGenero :img="''">PvP</CardGenero>
                <CardGenero :img="''">Cooperativo</CardGenero>
            </div>
        </div>

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