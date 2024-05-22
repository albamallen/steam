<template>
  <div class="card w-fit flex flex-col gap-3">
    <div class="flex flex-col p-7 rounded-3xl gap-5 bg-g800">
      <SquareImg class="w-72" :url="'sampleimg.jpg'"></SquareImg>
      <div class="downButtons flex gap-5 items-center">
        <Button :color="'primary'">{{ price }}€</Button>
        <Button :icon="'shop'"> </Button>
        <Button :icon="'like'"></Button>
      </div>
    </div>
    <div class="text flex justify-between">
      <h4><slot></slot></h4>
      <Tag></Tag>
    </div>
  </div>
</template>

<script setup>
import Tag from "./mockComponents/Tag.vue";
import Button from "./mockComponents/Button.vue";

const props = defineProps({
  price: String,
});

let price = "";
price = props.price;
if (price == "" || price == undefined) {
  price = "13.95";
}
</script>

<style lang="sass" scoped></style>
