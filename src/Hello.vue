<template>
    <div>
        <h2>Nama : {{ nama }}</h2>
        
        <h2>Umur : {{ umur }}</h2>
    </div>
</template>

<script>
export default {
    data(){
        return{
            nama : 'Khalid Ibrahim',
            umur : 22
        }
    },

    mounted(){
        this.umur = this.umur + 3;
    }
}

</script>

<style scoped>

</style>