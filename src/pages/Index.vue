<template>
  <div>
    <q-page class="flex flex-center column">
      <img alt="Quasar logo" src="~assets/quasar-logo-full.svg" />
      <h1>
        Crie interfaces de usuário VueJS de alto desempenho em tempo recorde.
      </h1>
      <!-- Para uma rota: <q-btn to="/start/pick-quasar-flavour" label="To Docs index" outline color="purple" />
       -->
      <q-btn color="positive" class="btn-start" label="Começar" />
      <Feature />
    </q-page>
  </div>
</template>

<script>
import Feature from '../components/Features'

export default {
  name: 'PageIndex',
  components: {
    Feature
  }
}
</script>

<style scoped>
h1 {
  font-size: 1.7rem;
  margin: 14px;
  text-align: center;
  line-height: 1.2;
}

.btn-start {
  font-size: 22px;
  border-radius: 14px;
}
</style>
