<template>
  <div
    :class="`card flex flex-col gap-5 ${textColor} p-6 w-[400px] rounded-3xl ${background} `"
  >
    <div class="topTags flex gap-2">
      <Tag></Tag>
      <Tag></Tag>
    </div>
    <SquareImg class="w-fill" :url="props.img"></SquareImg>
    <div class="text flex flex-col gap-16">
      <h4>{{ props.name }}</h4>
      <p class="text-primary">New Release</p>
      <p><slot></slot></p>
      <div class="downBottoms flex gap-5 items-center">
        <Button :color="'primary'">13,95€</Button>
        <Button :icon="'shop'"> </Button>
        <Button :icon="'like'"></Button>
      </div>
    </div>
  </div>
</template>

<script setup>
import Tag from "./mockComponents/Tag.vue";
import Button from "./mockComponents/Button.vue";

const props = defineProps({
  color: String,
  name: String,
  img: String,
});
let background = "";
let textColor = "";
if (props.color == "dark") {
  background = "bg-g800";
  textColor = "text-white";
} else if (props.color == "light") {
  background = "bg-g100 box-border border-2 border-black";
  textColor = "text-black";
}
</script>

<style lang="sass" scoped></style>
