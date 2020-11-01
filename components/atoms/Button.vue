<template>
  <div class="container">
        <button 
            class="button btn btn-primary" 
            @click="$emit('klik-button')">
            {{titleBtn}}
        </button>
  </div>
</template>

<script>
export default {
    props: {
        titleBtn: {
            type: String,
            default: 'DAPTAR',
        }
    }
}
</script>

<style>
    .button {
        
        border-radius: 5px;
              
    }
</style>