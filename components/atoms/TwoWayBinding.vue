<template>
  <div>
    <p>{{ message }}</p>
  <input v-model="message" class="text-green-900 focus:text-red-600" />

  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Your Name',
      count: 4
    }
  }
}

</script>
