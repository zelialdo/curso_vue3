<template>
  <div>
    <h1>
      Ola vue!
    </h1>
    <p>Meu Nome é {{ nome }} e trablho como {{ profissao }}</p>
  </div>
</template>

<script>
export default {
  name: 'PrimeiroComponente',
  data() {
    return{
      nome: "Zelialdo",
      profissao: "Programador"
    }
  }
}
</script>