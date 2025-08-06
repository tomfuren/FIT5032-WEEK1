<template>
  <div class="my-name">
    <p @click="changeName">Hello、{{ name }}</p>
  </div>
</template>

<script>
export default {
  name: 'MyName',
  data() {
    return {
      name: 'Tomoki'
    }
  }
}
</script>

<style scoped>
.my-name {
  font-size: 1.2rem;
  cursor: pointer;
  color: #fff;
}
.my-name:hover {
  color: #007bff;
}
</style>