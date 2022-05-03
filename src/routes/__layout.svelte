<nav>
  <a href="/sk-static-route-html/">Home</a>
  <a href="/sk-static-route-html/test1">Test #1</a>
  <a href="/sk-static-route-html/test2.html">Test #2</a>
</nav>
<main>
  <slot />
</main>

<style>
  nav {
    text-align: center;
  }
  main, nav {
    max-width: 500px;
    margin-inline: auto;
    font-family: Helvetica, sans-serif;
  }
</style>
