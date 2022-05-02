<h1>Testing routes</h1>
<ol>
  <li>build this repo <code>npm run build</code></li>
  <li>host a static site <code>cd build && python -m http.server</code></li>
  <li>visit /test1 (in a new tab) will <b>not</b> work</li>
  <li>visit /test2 (in a new tab) will work</li>
</ol>

<style>
  code {
    background-color: #ddd;
    padding: 0.3rem 1rem;
  }
  ol li {
    margin-block: 0.6rem;
  }
</style>
