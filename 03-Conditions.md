## Conditions

### Truthy/Falsy
* `undefined` falsy
* `0` falsy
* `1` truthy
* `null` falsy
* `'str'` truthy

* `!bool`

### if

```javascript
if (i === 1) {
    // do stuff
}
```

### if/else

```javascript
if (i === 1) {
    // do stuff
} else {
  
}
```

### if/else if

```javascript
if (i === 1) {
    // do stuff
} else if (i === 2) {
  
}
```

### switch

```javascript
switch (int) {
  case 2:
    // do stuf
    break;
  case 3:
    // do stuf
    break;
  default:
    // do stuff
    break;
}
```

### Ternary

```javascript
const test = isTrue ? true : false 
```

### Scope

```javascript
const i = 12
if (i < 13) {
    const j = 4
}
console.log(j);
```
