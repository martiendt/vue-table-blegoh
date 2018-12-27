<template>
  <div class="home">
    Vue table blegoh
    <hr>
    <vue-table v-bind:data="users"></vue-table>
  </div>
</template>

<script>
import VueTable from 'vue-table-blegoh'

export default {
  name: 'home',
  components: {
    VueTable
  },
  data () {
    return {
      users: [
        {
            "id": 0,
            "first_name": "Lorraine",
            "last_name": "Fields",
            "gender": "female",
            "age": 20,
            "eyeColor": "green",
            "email": "lorrainefields@grok.com",
            "balance": "$1,189.15",
            "phone": "+1 (901) 442-3257",
        },
        {
            "id": 1,
            "first_name": "Stanton",
            "last_name": "Hebert",
            "gender": "male",
            "age": 28,
            "eyeColor": "green",
            "email": "stantonhebert@hopeli.com",
            "balance": "$3,288.77",
            "phone": "+1 (841) 405-3690",
        }
      ]
    }
  }
}
</script>
