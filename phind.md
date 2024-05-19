# Phind prompt

- что за код
- что делает код


# что за код 

```js
var xmlHttp = new XMLHttpRequest()

xmlHttp.onreadystatechange = function() {
    if (xmlHttp.readyState == XMLHttpRequest.DONE) {
        alert(xmlHttp.responseText);
    }
}

xmlHttp.open( "POST", "http://"+host+":"+port, true );

xmlHttp.send(dt)
```
