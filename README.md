一个使用助记词和区分词来生成密码的网页。
如使用123456作为助记词，github作为区分词，然后可以生成10位带有大小写，标点符号和数字的密码。
fork的是这个项目：https://github.com/Wsine/seekpassword
## 自定义
### 自定义加密用字词
修改
/src/seekpass_word.js文件中的str字符串：原项目是：unlovesnow1990090127xykab
可以改成自己喜欢的内容，这样生成的密码也会发生变化。
使用时可以使用GitHub Pages搭建的网页版，也可以直接下载下来然后本地打开index.html文件后在浏览器使用。（个人更建议这种。）
### 自定义长度
修改/src/seekpass_word.js 37.38行（大致位置）的数字10，将其修改成需要的长度即可。
