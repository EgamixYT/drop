<template>
    <div class="">
        <p v-for="i of 100" :key="i">
      {{i}} {{page}} <br>
    </p>
        
    </div>
</template>

<script>
export default {
    layout: 'admin',
    data(){
        return{
            page: this.$route.params.name
        }
        
    }
}
</script>