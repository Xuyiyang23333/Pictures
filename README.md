## 前言

昨天我发现Vercel可以用来搭建静态博客，而且不仅仅是作为生成器，直接上传静态网页文件也是可以的。

刚刚我在厕所里蹲着的时候想到了一个绝妙的主意，在Github创建一个仓库，再让Vercel把这个仓库部署到服务器上，这不就是一个图床吗？

实践出真知，我动手开始尝试。

## 正文

我曾经为了蹭Github的issues图床，创建了一个仓库叫做`Pictures`，也往里面传了几张图片，文件目录是这样的。

![firefox_2020-08-28-08-07-50-1598573270.png](https://i.loli.net/2020/08/28/zCED8LvrwjZYcTm.png)

直接用Vercel的`Import Git Repository`功能导入。

![firefox_2020-08-28-08-08-47-1598573327.png](https://i.loli.net/2020/08/28/9d7xkR6ViXCmGyU.png)

如果没有index.html，Vercel就会提供一个简单的文件浏览器。

![firefox_2020-08-28-08-09-09-1598573349.png](https://i.loli.net/2020/08/28/pehKUNzAVZYxDyC.png)

测试一下，图片地址确实是静态的，可以用作图床。

![Shiina_Mashiro_with_knife](https://img.yxyy.top/2020/08/Shiina_Mashiro_with_knife.jpg)
