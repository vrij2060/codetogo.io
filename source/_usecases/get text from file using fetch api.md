---
extends: _layouts.usecase
date: 2018-03-12
link: #
reference: #
related: fetch api
category: fetch api
---


```javascript
    fetch('filename.txt')
    .then((res)=>res.text())
    .then((data)=>{
        console.log(data);
    })
    .catch((e)=>console.log(e));
```

<pre class="output">Data</pre>
