---
---

<pre id="debug-json">
</pre>

<script>
  var debug = {{ site | jsonify }};

  document.getElementById('debug-json').innerText = JSON.stringify(debug, null, 2);
</script>
