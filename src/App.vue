<template>
  <h1 class="title" @click="likes += 1">click likes -{{ likes }}</h1>
</template>

<script>
export default {
  data() {
    return {
      likes: 0,
    };
  },
};
</script>

<style>
.title {
  color: orange;
}
</style>
