<template>
  <div class="footerPageContainer">
    <div class="footerContainer">
      <a href="">Created by Alex Cowls</a>
      <!-- <a href="https://github.com/Quermz/vue-webstore">
        <i class="fa-brands fa-github"></i>
      </a> -->
    </div>
  </div>
</template>

<script>
  export default {
    setup() {
      return {};
    },
  };
</script>

<style scoped>
  a {
    text-decoration: none;
    display: flex;
  }
  *:visited {
    text-decoration: none;
    color: black;
  }

  i:hover {
    scale: 1.1;
  }
  .footerPageContainer {
    display: flex;
    justify-content: center;
    background: #f8f9fa;
  }
  .footerContainer {
    width: 1200px;
    padding: 1rem;
    display: flex;
    /* background: #f8f9fa; */
    min-height: 3rem;
    justify-content: center;
    align-items: center;
  }

  i {
    font-size: 30px;
  }
</style>
