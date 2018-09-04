# Control Flow

```javascript
function one(input, result1) {
  function two(result2) {
    function three(result3) {
      function four(output) {
        /* do something with output */
      });
    });
  });
});
```

Perhaps should be written as:
```javascript
controlFlow.doStuff(input, function (output) {
  /* do something with output */
});
```
