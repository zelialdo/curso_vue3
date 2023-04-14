<template>
  <div>
    <h1>
      Ola vue!
    </h1>
    <p>Meu Nome é {{ nome }} e trablho como {{ profissao }}</p>
    <MultiplosEventos />
    <Reutilizacao />
    <Reutilizacao />
    <Reutilizacao />
    <Reutilizacao />
  </div>
</template>

<script>
import MultiplosEventos from './MultiplosEventos.vue';
import Reutilizacao from './Reutilizacao.vue';

export default {
  name: 'PrimeiroComponente',
  components: {
    MultiplosEventos,
    Reutilizacao
  },
  data() {
    return{
      nome: "Zelialdo",
      profissao: "Programador"
    }
  }
}
</script>