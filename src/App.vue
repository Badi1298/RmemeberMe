<template>
  <the-header></the-header>
  <the-resources></the-resources>
</template>

<script>
import TheHeader from './components/layouts/TheHeader.vue';
import TheResources from './components/learning-resources/TheResources.vue';

export default {
  components: {
    'the-header': TheHeader,
    'the-resources': TheResources,
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Lato&display=swap');

* {
  box-sizing: border-box;
}

html {
  font-family: 'Lato', sans-serif;
}

body {
  margin: 0;
}

button {
  font-family: inherit;
}
</style>
