<template>
    <div>
        <h1>Deretan bilangan ganjil</h1>
        <h4>{{ bilangan }}</h4>

        <button v-on:click="tambah">Tambah</button>

    </div>
</template>



<script>
    export default{
        data(){
            return{
                bilangan : 1
            }
        },

        //v-on = untuk menambahkan event listener pada suatu element
        //v-model = 2 databinding

        methods:{
            tambah(){
                this.bilangan += 2;
            }
        }
    }
</script>


<style scoped>

</style>