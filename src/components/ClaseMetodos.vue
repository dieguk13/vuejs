<template>
  <div>
    <span>
      <h2>
        {{ mostrarmensaje() }}
      </h2>
    </span>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name2: "prueba parrafo",
    };
  },

  methods: {
    mostrarmensaje() {
      return this.name2;
    },
  },
};
</script>

<style lang="scss" scoped></style>
