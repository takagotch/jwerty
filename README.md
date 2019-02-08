### jwerty
---
https://github.com/keithamus/jwerty

```js
jwerty.key('ctrl+shift+P', function() { [...] });
jwerty.key('x+x+P', function() { [] } );

jwerty.key('^+x+P/X+x+P', function(){ [] });

jwerty.key('^+x+{X+x+P', function(){ [] });

jwerty.key('x,x,x,x,x,x,x,x,x,x', function(){ [...] });

jwerty.key('ctrl+[a-c]', function(){ [] });

var h = jwerty.key('ctrl+shift+P', function() { [] })
h.unbind()

$('#myinput').bind('keydown', jwerty.event('^+x_P/x+x+p', function(){ [] }));

function(event){
  if( jwerty.is('^+x+p', event) ){
    [...]
  }
}

jwerty.fire('enter', 'input:first-child', '#myForm');
```

```
```

```
```


