<template>
    <footer>
        <span>💻 with ❤ &amp; <a href="//vuejs.org">Vue.js</a> in Mexico</span>
    </footer>
</template>


<script>
export default { 
  name: 'app-footer'
}
</script>

<styles scoped>
  footer {
    box-sizing: border-box;
    background-color: #cfd8dc;
    position: absolute;
    bottom: 0;
    left: 0;
    padding: 1rem;
    width: 100%;
  }

  a {
      text-decoration: none;
      color: #546E7A;
    }

</styles>