### esdoc
---
https://github.com/esdoc/esdoc

```js
export default class MyClass {
  sum(a,b){
    return a + b;
  }
}

describe('MyClass has foo bar feature', ()=>{
  it('MyClas#baz returns magic value', ()=>{
    assert(true);
  });
});
```

```
open ./docs/index.html
cd your-project/
npm install --save-dev esdoc esdoc-standard-plugin
./node_modules/.bin/esdoc -h
```

```
{
  "source": "./src",
  "destination": "./docs",
  "plugins": {
    {"name": "esdoc-standard-plugin"}
  }
}
```

