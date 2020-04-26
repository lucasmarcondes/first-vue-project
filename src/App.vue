<template>
  <body id="container">
    <the-header id="header"></the-header>
    <router-view id="content"></router-view>
    <the-footer id="footer"></the-footer>
  </body>
</template>
<script>
import TheHeader from './components/TheHeader';
import TheFooter from './components/TheFooter';

export default {
  components: {
    TheHeader,
    TheFooter
  }
};
</script>
<style scoped>
#container {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
#content {
  flex-grow: 1;
}
</style>
