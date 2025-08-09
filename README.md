# Anti-counterfeiting-system
现支持功能：
1、防伪查询页访问、防伪直接查询（通过链接或二维码直接访问）、防伪页中转查询、短链访问数据都单独统计，每个防伪码的访问数据也做了单独统计
![image](https://github.com/user-attachments/assets/5abe6b99-2ef5-498e-b09a-e214aa0996a1)
![image](https://github.com/user-attachments/assets/c311f189-c646-4a9b-998a-de0b50bc1df2)
2、素材管理：支持上传图片、视频、音频，方便后续调用，不用重复上传文件。
3、短链接，将外部的长链接绑定自身域名做成短链接，访问短链接跳转到指定的长链接，比如：https://a.fdxs99.com/36fM
访问后是直接跳转到百度，并且支持配置短链接域名、落地域名、入口域名，还可自由设置访问限制，如仅限制在微信访问，那在微信外访问就会显示。各自加入了按钮，可以自由触发关闭跟开启短链接，不用的时候也不用直接删除，防止后续要重新启用。

![image](https://github.com/user-attachments/assets/68ef49ad-f4fc-4076-8a82-10162c62970f)
4、防伪码直接访问做了一个网页，网页中放置文件的位置可以自由上传图片、视频或音频，放VX二维码也可以直接扫码添加，文件位置的下方还可放置超链接，比如跳转到自己品牌搭建的h5商城，这个页面也可自由设置访问限制。页面的背景也可以简单做更换。

![image](https://github.com/user-attachments/assets/430ac542-dcae-442f-b897-088c8a2b0715)

5、权限精细化。每个页面每个功能都单独赋予权限，并且做了双重验证，前端+后端都验证通过了才能进行对应操作。
![image](https://github.com/user-attachments/assets/5767b84d-e763-4238-b5ec-2a3af9e65261)
6、防伪码可以自定义自己想要的编码格式，以及对应的产品名称，还可以随时编辑，并且各自加入了按钮，可以自由触发关闭跟开启短链接，不用的时候也不用直接删除，防止后续要重新启用，支持重置访问。
7、防伪码支持批量生成、手动新建、表格批量导入增加或修改、表格导入批量删除等。

<img width="1362" height="662" alt="image" src="https://github.com/user-attachments/assets/13474d59-1c9e-41a2-adf7-e55ad9796a3c" />

8、访问ip可以手动加入黑名单或白名单。如果访问某个页面超过20次限制访问7天，超过50次永久限制访问，并且会跳转到指定的封禁显示页。黑名单封禁访问也可以指定限制访问指定页面，包括时长可选7天、永久封禁或自定义日期。
![image](https://github.com/user-attachments/assets/e6b1b33d-acf6-4448-abd9-3df87f71edb5)
9、支持自建产品。产品跟防伪码做绑定。这样就不用每次都新建一个防伪码，然后产品名称或其他内容还要再次输入或上传。
![image](https://github.com/user-attachments/assets/ea88cee2-ff8d-4cbb-82dd-f984f4c58749)

10、防伪直接查询支持多个样式页面切换，后续会有三个样式页面，分为售后+防伪查询 / 调取微信内部扫一扫扫码防伪查询 / 直接扫码查询，页面后续也可以支持个性化定制，防伪码有在后端做了设置，可以随身切换你要的样式页面

![image](https://github.com/user-attachments/assets/b4a89c26-42f5-407a-b944-499eb9d8cefc)

![image](https://github.com/user-attachments/assets/2da0eea5-5351-401c-a682-2c16f059c1b9)

![image](https://github.com/user-attachments/assets/a86db6ff-fe73-4d26-bc0b-d2bffeb791bf)

11、产品管理、防伪码管理支持多选进行删除、批量生成二维码并下载成压缩包，批量生成链接并下载成表格（方便链接转二维码，主要针对有美化二维码需求的，）,自定义导出防伪码链接

<img width="1376" height="695" alt="image" src="https://github.com/user-attachments/assets/ddcea3dc-4159-46fb-bffb-a3184bbf529a" />
<img width="1386" height="737" alt="image" src="https://github.com/user-attachments/assets/51f87272-fd75-4fb4-9713-b0ac9ee6d31a" />

12、登录记录、操作记录

<img width="1377" height="694" alt="image" src="https://github.com/user-attachments/assets/9e3ab107-bce4-4073-b40f-d474e94cca6d" />

<img width="1351" height="552" alt="image" src="https://github.com/user-attachments/assets/7434e021-3beb-4676-9757-0f40bb3e3859" />

13、产品管理支持直接复制现有商品以及自定义勾选要在样式页面显示的字段，不勾选则是默认不显示
<img width="1332" height="719" alt="image" src="https://github.com/user-attachments/assets/cfc4e43c-4973-477d-9bdc-8f3a77cd7403" />

<img width="681" height="679" alt="image" src="https://github.com/user-attachments/assets/80dd330c-fd61-49d4-a94b-701a38cfdcbc" />

14、系统基础配置

<img width="1336" height="751" alt="image" src="https://github.com/user-attachments/assets/e53ffd52-3636-4ff0-8838-1106a97e73a8" />


待上线功能

1、售后板块（前端收集售后信息，后端存储提醒）+回调提醒

2、窜货预警，产品做销售区域绑定后，如访问IP不是当前区域，则会给出预警提醒

![image](https://github.com/user-attachments/assets/dba0c410-8bd4-4ca3-8d41-03244da01b90)

3、日常数据优化，账号增加经销商绑定，比如账号绑定了经销商A，登录后只能查看到经销商A创建的防伪码以及对应的数据。


一物一码、防伪码查询系统，支持直接查询跟链接扫码跳转查询
采用PHP7.4+JS+CSS+Mysql5.7进行编写
滚动条采用simplebar  二维码生成采用qrcode框架 部分js代码采用jquery-3.6.0框架 图表绘制采用chart.js
拥有完整的权限设置，可以注册员工账号分配不同权限
![image](https://github.com/user-attachments/assets/30b536cf-4a15-4c58-adce-125a2fcdd85e)
![image](https://github.com/user-attachments/assets/7195dcbc-e8c7-4f86-a499-108f67e3ba9f)
![image](https://github.com/user-attachments/assets/1599c7fa-968b-4dc6-8d78-87171f2691b9)
![image](https://github.com/user-attachments/assets/4d3b5ccf-7bbd-471c-a73e-a5f9af8ef6df)
![image](https://github.com/user-attachments/assets/1cebe67c-e320-4f1f-aa6d-41b284e173f2)
![image](https://github.com/user-attachments/assets/f28185c0-f9c2-41db-85cb-64c96f756ee9)
防伪码查询方式支持两种，一种是各种途径直接进入链接显示产品信息的，并且可以限制在指定设备或渠道访问，如只能在微信端打开，如果不再微信端打开则会提示
![image](https://github.com/user-attachments/assets/aca1695a-82a2-4103-b2a7-adb703dee96b)
![image](https://github.com/user-attachments/assets/18f3d96a-6e00-4f88-888a-a9d5137c36d6)
另外一种则就是通过中转调起手机摄像头扫码来查询防伪，一般用于公众号上
![image](https://github.com/user-attachments/assets/91b36a48-1c21-4724-98bd-0de14da2d3e1)
![image](https://github.com/user-attachments/assets/9dc98540-734d-4f46-a129-55bdecea6f15)
短链接功能也是一样，有限制指定渠道打开的功能
![image](https://github.com/user-attachments/assets/75094af8-d77f-4d95-a393-9e3fce9dfd06)
![image](https://github.com/user-attachments/assets/73e393f2-6d16-4dcf-b600-e60cddce1b7a)
![image](https://github.com/user-attachments/assets/8722a08c-2dc3-43ff-80eb-0eac6bb226fa)
![image](https://github.com/user-attachments/assets/07737bf8-c5e5-4602-98ee-be36806600b2)
![image](https://github.com/user-attachments/assets/2b559f19-c3f3-4159-8a31-2efc52b0939a)
完整的操作记录
![image](https://github.com/user-attachments/assets/37d0e256-dca8-4844-8c22-8e5f78122723)

买断式源码交付，低成本搭建防伪体系以及平台

有需要或想体验一下的可以扫码添加咨询

![image](https://github.com/user-attachments/assets/279dcb9f-1074-4d88-840d-3f631764540e)

上方的添加不上可以添加下方这个

![f9b6a311b4c6bfcc02b70e5e0947efca](https://github.com/user-attachments/assets/d3837cbb-e3a1-4424-b62c-77c1945b7db2)

