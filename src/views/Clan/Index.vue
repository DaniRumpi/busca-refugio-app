<template>
  <section class="clan">
    <h1>Logeado: {{ isLogged }}</h1>
    <h3>Clan</h3>
  </section>
</template>

<script>
  // import service from '@/services/auth';
  import { mapGetters } from 'vuex';

  export default {
    data() {
      return {};
    },
    methods: {},
    computed: {
      ...mapGetters( {
        isLogged: 'isUserLogged',
      } ),
    },
  };
</script>

<style lang="stylus" scoped>
</style>
