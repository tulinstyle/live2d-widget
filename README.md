

## 使用

如果你是小白，或者只需要最基础的功能，那么只用将这一行代码加入 html 页面的 `head` 或 `body` 中，即可加载看板娘：
```xml
<script src="https://fastly.jsdelivr.net/gh/tulinstyle/live2d-widget@latest/autoload.js@latest/autoload.js"></script>
```
添加代码的位置取决于你的网站的构建方式。例如，如果你使用的是 [Hexo](https://hexo.io)，那么需要在主题的模版文件中添加以上代码。对于用各种模版引擎生成的页面，修改方法类似。  
如果网站启用了 PJAX，由于看板娘不必每页刷新，需要注意将该脚本放到 PJAX 刷新区域之外。

