<template>
  <div>
    <PrimeiroComponente />
    <LifeCycle/>
  </div>
</template>

<script>
  import PrimeiroComponente from './components/icons/PrimeiroComponente.vue'
  import LifeCycle from './components/icons/LifeCycle.vue'

export default {
  name: 'App',
  components: {
    PrimeiroComponente,
    LifeCycle
  }
}
</script>