<script>
import ClaseMetodos from "../src/components/ClaseMetodos.vue";

export default {
  components: {
    ClaseMetodos,
  },
  data() {
    return {
      name: "prueba dinamica",
    };
  },

  created() {
    alert("created");
  },
  mounted() {
    alert("mounted");
  },
  updated() {
    alert("updated");
  },
  destroyed() {
    alert("destroyed");
  },
  computed: {},
  methods: {},
  //watch
};
</script>
<template>
 

  <clase-metodos> </clase-metodos>
</template>

<style>

</style>
