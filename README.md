# usbnode.js
usb stick on node
```

node.exe
server.js
index.html
/public
/note
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

//note
//localhost:8080/note/xyz.txt
//note以下に適当にファイル名をつけるだけで、そのファイル名のテキストファイルが生成される。

```
