## JavaScript Loop Snippets

### [jfore] forEach

```javascript
${1:myArray}.forEach(function(${2:element}) {
    ${3}
});
```

### [jfori] for in

```javascript
for (${1:prop} in ${2:obj}) {
  if (${2:obj}.hasOwnProperty(${1:prop})) {
    ${3}
  }
}
```

### [jfor] for

```javascript
for (var i = ${1:0}, len = ${2:10}; i ${3:<=} len; i${4:++} ) {
  ${5}
}
```