---
title: picgo图床使用
date: 2022-06-17 20:00:17
tags:
---



## 下载picgo

[Releases · Molunerfinn/PicGo (github.com)](https://github.com/Molunerfinn/PicGo/releases)

安装部分就不用说了，一直下一步就可以了



这里推荐几个图床

[Image Upload - SM.MS - Simple Free Image Hosting](https://sm.ms/)

[imgurl (imgurl.org)](https://imgurl.org/)

[GitHub](https://github.com/)

## 获取github访问token

首先新建一个空仓库

![image-20220617200932799](https://gitlab.com/shaonl/img/-/raw/main/img/2022/06/17_20_9_32_2022-06-17-20-09-32-caf800b2abdfd4238cdf6d9a429fb6fa-b208dd.png)



公开是必选的，其他随意

![image-20220617201011646](https://gitlab.com/shaonl/img/-/raw/main/img/2022/06/17_20_10_11_2022-06-17-20-10-11-d9cce5f8b80e6d05b7b3c2f1a092d0aa-4ee27c.png)

再点击头像下方的设置

![image-20220617201156301](https://gitlab.com/shaonl/img/-/raw/main/img/2022/06/17_20_11_56_2022-06-17-20-11-56-663af5c6374bcaff96c6d13a98732de7-b55269.png)

选择  [Developer settings](https://github.com/settings/tokens)

![](https://gitlab.com/shaonl/img/-/raw/main/img/2022/06/17_20_13_48_2022-06-17-20-13-48-dca58dea6e0546bfb3887bde7167f71c-f26586.png)

创建一个令牌

![image-20220617201322733](https://gitlab.com/shaonl/img/-/raw/main/img/2022/06/17_20_13_22_2022-06-17-20-13-22-c96fe35fb2fdb4ffa40242cffdb3e6b0-4f0432.png)

选择repo即可，其他权限不需要，时间自己定

![image-20220617201512012](https://gitlab.com/shaonl/img/-/raw/main/img/2022/06/17_20_15_12_2022-06-17-20-15-12-c33e525f06cc9155a3809bf960f5235e-6058c7.png)

点击最下面的按钮即可获取token

![image-20220617201613315](https://gitlab.com/shaonl/img/-/raw/main/img/2022/06/17_20_16_13_2022-06-17-20-16-13-e8d456f30c2baf279c073260e217b670-28e0a5.png)

网页上会出token，网页别关，将这个值先复制到别的地方，因为只会显示一次

## 软件设置

打开picgo，设置相关参数因为软件自带的github设置有问题，上传总是失败，只好通过第三方插件来进行上传

打开软件，点击左侧列表中的插件设置

![image-20220617200545015](https://gitlab.com/shaonl/img/-/raw/main/img/2022/06/17_20_5_45_2022-06-17-20-05-45-3eb84e1ce6059b8fea5528eebc5f8d51-482e62.png)



![image-20220617202001687](https://gitlab.com/shaonl/img/-/raw/main/img/2022/06/17_20_20_1_2022-06-17-20-20-01-3e8cb08dcea1ed0ab290a0b5b42b9ca5-4ecc7e.png)

repo：组织名/仓库名 

branch: 选择分支

token：github中获取的一串字符

path: 不想将图片放在仓库根目录，则需要先在仓库中创建一个文件夹，之后填写该文件夹即可  如 img/

customUrl:  `https://cdn.jsdelivr.net/gh/用户名/仓库名@分支

点击确定即可

![](https://gitlab.com/shaonl/img/-/raw/main/img/2022/06/17_20_31_15_2022-06-17-20-31-15-09d5780dc2e0d296200e33733d6cf885-74c92d.png)

选择一张图片往里面拖可以看到上传成功的提示啦
