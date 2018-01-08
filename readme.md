> 一个演示XSS攻击和防护措施的简单Demo，后台使用的是Express.js

使用方法：

1. 下载源文件，确保在安装好nodejs(npm)之后切换到xssTest目录下
2. 执行`npm install`安装所需的npm包
3. 安装完毕后，使用`npm start`命令启动服务
4. 在浏览器中输入`localhost:3000`运行网页

在科技高度发达的今天，不少浏览器都自带了防止xss攻击的功能，为了演示效果，请在routes/index.js中打开注释禁用此功能。(在生产环境请务必不要这么做!)
