# 废话

这个repo目标就是记录自己的逆向学习过程，单纯是因为不记录就会忘的一干二净（）

> 准确来说是爬虫？毕竟玩的都太入门了

js逆向瞬息万变，混淆方式也是层出不穷，可能前几天学的东西，实操的时候反而就不行了，这种适合直播课来学然后尽快实操；

而app逆向由于可以找到老版本的app，所以存在很长的时效性，编写出来的爬虫代码也能长时间稳定运行；

> app由于兼容的问题，以及软件更新可以被hook的问题，这能让我们即使隔了几个月或者几年，代码以及接口内容都不改变；

目前逆向全流程的如下，你要是用到了就点个star就行，最好fork一下（说不定我被制裁了到时候仓库代码被删掉

> 本人水平有限，不是科班出身，有些地方说的不对的话，请大家直接提出，我改正一下；
>
> 部分内容是一些经典教程的，你们可以自己去找对应视频；其他的案例是我自己找来研究的；
>
> 很多资料都是网上公开的博客有的，有的可能忘了注明来源了， 看见了可以提醒一下，或者pr改一下

我也懒得写免责声明了，反正写了也没用（敏感的我不放上来不就好了，虽然我也没那个能力；



# 关于资料

- 优先考虑代码上传;

  > github文件大小限制

- 对于能抽象出来的重复代码可以去看第一个文件夹
- apk和jar包： 请点击 [网盘链接](https://pan.baidu.com/s/1f28fv9A39LruaMg4wx4QYA?pwd=uxw2) 下载（懒得搞其他网盘了，一顿百度网盘塞了）



下面是md分析链接和视频链接

具体也可以去文件夹中找，也可以直接看 [具体目录](#具体目录) 



# 具体目录

- 唯品会   v7.83.3

  > [图文流程](./3-app完整案例/1-唯品会/唯品会v7.83.3接口.md)



- 微博 【轻享版v6.4.6 and  极速版v10.9.8】

  > [图文流程](./3-app完整案例/2-微博/微博系列app接口逆向分析.md)
  
  - [【验证码登录接口】&【aid参数】](https://www.bilibili.com/video/BV17Xj2zHEKX/)
  - [【ck号登录&密码登录】&【s参数】](https://www.bilibili.com/video/BV1Cej9z2EWd/)
  - [【点赞&评论&回复&发帖&转帖】](https://www.bilibili.com/video/BV1kBjdzQEnz/)
  - [【超话签到】](https://www.bilibili.com/video/BV1usjdzaEG3/)
  
  
  
- 豆瓣 v7.100.0

  > [图文流程](./3-app完整案例/3-豆瓣/豆瓣app接口逆向分析.md)
  
  - [【frida反调试检测】 针对性绕过的分析&实现](https://www.bilibili.com/video/BV1gd7GzLEEM)
  - [【sig参数&常见登录接口】](https://www.bilibili.com/video/BV1Wx7czKEkt)



- 淘最热点 v2.3.3
  
  - [ sign签名的纯算&unidbg方案](https://www.bilibili.com/video/BV1E67AzeEhM)
  
  
  
- 海博tv v3.26

  > 只有frida脚本和py代码

  

- 喜马拉雅 v6.6.99.3
  
  > [图文流程](./3-app完整案例/6-喜马拉雅/喜马拉雅appV6.66.93逆向分析.md)
  
  - [登录接口参数逆向&unidbg补环境练习](https://www.bilibili.com/video/BV1AN7ezfEyc/)



- 美之图 v4.0.0

  > [图文教程](./3-app完整案例/7-美之图/美之图app接口逆向分析.md)



- 韩小圈 v6.5.3

  > [图文教程](./3-app完整案例/8-韩小圈/韩小圈app接口逆向分析.md)

  - [搜索接口&uk参数&sign参数&rpc解密响应体](https://www.bilibili.com/video/BV12QTkzAED5/)

