# query2json

> 1 line javascript

```js
export default q => [{}].concat(q.split("&")).reduce((r, p, i, o, [k, v] = p.split('=')) => ((r[k] = v), r))
```
