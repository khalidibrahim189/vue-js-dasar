<template>
    <div>
        <h2>Penggunaan v-model pada vue js</h2>

        <h4>{{ pesan }}</h4>

        <input v-model="pesan" />
    </div>
</template>

<script>
    export default{
        data(){
            return{
                pesan:''
            }
        }
    }
</script>
