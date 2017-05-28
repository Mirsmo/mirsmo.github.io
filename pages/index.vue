<template lang="html">
  <div class="container">
    <h1 class="title">Mirsmo</h1>
    <h2 class="subtitle">Store coming soon</h2>
    <a href="http://instagram.com/hellomirsmo">Follow on Instagram</a>
  </div>
</template>

<script>

</script>

<style lang="scss">

  $ikb: #002EA7;
  $pink: #ffb2a8;

  .container {
    left: 50%;
    padding: 4vh;
    position: absolute;
    text-align: center;
    top: 50%;
    transform: translate(-50%,-50%);
  }

  h1 {
    color: white;
    font-size: 8vh;
    letter-spacing: .25em;
    padding-left: .25em;
    text-transform: uppercase;
  }

  h2 {
    font-size: 2vh;
    letter-spacing: .25em;
    padding-left: .25em;
    text-transform: uppercase;
  }

  a {
    border: 1px solid white;
    display: inline-block;
    padding: .5em 1em;
    color: white;
    text-decoration: none;
    &:after {
      content: ' →';
      display: inline-block;
      padding-left: .25em;
      transition: transform .25s ease;
    }
    &:hover {
      &:after {
        transform: translateX(.25em);
      }
    }
  }
</style>
