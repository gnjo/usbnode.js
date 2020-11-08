# usbnode.js
usb stick on node
```

//アプリケーションはフォルダ駆動、そのフォルダのindex.htmlがアプリケーションとなる。
//配下のディレクトリの存在をserver.jsは自動で判断する。

cmd.bat
node.exe
server.js
/public
 index.html
/note
 index.html


//
//cmd.bat
node.exe server.js localhost:8080

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
