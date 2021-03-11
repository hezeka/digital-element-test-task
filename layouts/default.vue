<template>
  <div>
    <Nuxt />
  </div>
</template>
<script>
window.addEventListener('scroll', function(event) {
  let scrollTop = (document.documentElement && document.documentElement.scrollTop) || (document.body && document.body.scrollTop)
  // console.log(scrollTop)
  if (scrollTop > 30) {
    document.querySelector('header').classList.add('fixed');
  } else {
    document.querySelector('header').classList.remove('fixed');
  }
});
</script>
<style>
html {
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

body {
  background-color: #fff;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

button {
  border: none;
  outline: none;
  background-color: transparent;
  cursor: pointer;
}

input, textarea, button, body {
  font-family:
    'Gilroy',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
}
</style>
