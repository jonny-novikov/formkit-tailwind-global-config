<template>
  <img
    class="logo"
    width="132"
    src="https://cdn.formk.it/brand-assets/formkit-logo-white.svg"
    alt="FormKit Logo"
  />
  <div class="example-wrap">
    <ExampleInput />
  </div>
  <div class="credit">
    For more information, read the documentation at
    <a href="https://formkit.com">formkit.com</a>
  </div>
</template>

<script>
import ExampleInput from './components/ExampleInput.vue';

export default {
  components: {
    ExampleInput,
  },
};
</script>

<style>
html,
body {
  min-height: 100%;
}
body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica,
    Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';
  background: linear-gradient(to bottom right, #083b47, #011418);
}
.logo {
  display: block;
  margin: 1em auto;
}
.example-wrap {
  box-sizing: border-box;
  background: white;
  padding: 1.5em;
  width: 32em;
  margin: 1.5em auto;
  max-width: calc(100% - 3em);
  border-radius: 0.5em;
}

.example-wrap pre {
  font-size: 0.875em;
  font-family: monospace;
  bottom: 0;
  padding: 1.5rem;
  margin: 1.5em -1.5rem -1.5rem -1.5rem;
  background-color: rgba(50 50 250 / 10%);
  display: block;
}

.credit {
  font-size: 0.865em;
  color: white;
  -webkit-font-smoothing: antialiased;
  -moz-font-smoothing: grayscale;
  max-width: 20em;
  text-align: center;
  margin: 1em auto;
  opacity: 0.8;
}
.credit a {
  color: orange;
}
</style>
