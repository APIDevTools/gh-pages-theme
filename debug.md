---
---

<pre id="debug-json">
</pre>

<script>
  var debug = JSON.parse(`
    {{ site | jsonify | xml_escape }}
  `);

  document.getElementById('debug-json').innerText = JSON.stringify(debug, null, 2);
</script>
