首先创建一个仓库

必须设置为公开

手动往仓库中添加图片

![image-20220425210431576](https://cdn.jsdelivr.net/gh/Ming411/imgRepo/img/image-20220425210431576.png)



**使用cdn加速后的访问形式**

https://cdn.jsdelivr.net/gh/+用户名/仓库名/图片具体路径

例如：https://cdn.jsdelivr.net/gh/Ming411/imgRepo/wallhaven.png

原生git访问

https://raw.githubusercontent.com/你的用户名/你的仓库名/main/文件路径来访问所上传的图片。



**PicGo 配置**

- 打开 PicGo 软件，找到`图床设置`中的`GitHub图床`，填写相关信息。

- - **设定仓库名【必填】**：填写`你的用户名/你的仓库名`，比如我的 Ming411/imgRepo
  - **设定分支名【必填】**：填写`main`
  - **设定Token【必填】**：在Github主页点击自己头像后，依次选择【Settings】->【Developer settings】->【Personal access tokens】->【Generate new token】，填写Note描述（随便），设置过期时间Expiration为永不过期No expiration，设定勾选【repo】，然后点击下方的【Generate token】生成一个Token，这个Token只会显示一次，自行保存，然后复制到 PicGo 中。
  - 指定存储路径【选填】：填写图片要存储的路径，比如填【img/】，这样就会在仓库下创建一个名为 img的文件夹，图片将会储存在此文件夹中，这里不填。
  - **设定自定义域名【选填】**：图片上传后，PicGo 会按照【自定义域名+上传的图片名】的方式生成访问链接，放到剪贴板上，因为我们要使用 jsDeliver 进行加速，因而这里设置为`https://cdn.jsdelivr.net/gh/你的用户名/你的仓库名`，比如我设置为**https://cdn.jsdelivr.net/gh/Ming411/imgRepo**



![image-20220425210925544](https://cdn.jsdelivr.net/gh/Ming411/imgRepo/img/image-20220425210925544.png)