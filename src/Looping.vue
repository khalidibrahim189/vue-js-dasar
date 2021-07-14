<template>
  <div>
    <h2>Looping vue js</h2>
    <table border="1">
      <tr v-for="hari in namaHari" v-bind:key="hari">
        <td>{{ hari }}</td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {
  data() {
    return {
      namaHari: [
        "Senin",
        "Selasa",
        "Rabu",
        "Kamis",
        "Jumat",
        "Sabtu",
        "Minggu",
      ],
    };
  },
};
</script>

<style scoped></style>
