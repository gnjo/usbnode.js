# usbnode.js
usb stick on node
```

node.exe
server.js
index.html
/public
cmd.bat

//
//cmd.bat
node.exe server.js localhost:8080 public

//index.html
//
let baseurl='localhost:8080'
let filepath='public'
let filename='aaaa.jpg'
let url=[baseurl,filepath,filename].join('/')
fetch(url,{method:'post',body:base64data}) //upload
fetch(url) //get

//server.js

let is={}
is.base64
function toBlob(base64){
//cut this 
//data:*/*;base64
}


```
