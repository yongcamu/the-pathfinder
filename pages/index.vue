<template>
  <div class="index">
    <div class="access">
      <button @click="login">
        Login
      </button>
      <button @click="register">
        Register
      </button>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    login () {
      this.$router.push('/play/explore')
    },
    register () {
      this.$router.push('/play/explore')
    }
  }
}
</script>

<style lang="scss" scoped>
.index {
  height: 100vh;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.access {
  button {
    display: block;
    width: 100%;
  }
}
</style>
