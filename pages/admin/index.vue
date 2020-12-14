<template>
  <div>
    <p v-for="i of 100" :key="i">
      {{i}} <br>
    </p>
  </div>
</template>

<script>
export default {
    layout: 'admin',
    
}
</script>

