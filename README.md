# 在线照片边框水印 | Camera Vision
为您的照片添加自定义相框和水印，支持照片参数读取和批量导出，多种相框模板选择，开放多种参数自定义。

在线预览地址（dev）：[lookcv.com](https://lookcv.com)

# 项目介绍
## 用户痛点
大部分摄影朋友都是电脑上调色出图，然后传到手机上加边框水印，电脑上需要下载应用才能完成类似需求。下载软件在体验上的一个很重的操作，要担心木马病毒、广告入侵、磁盘占用等等。对于这种使用频次不高且功能单一的应用，最合适的是一个即开即用的网页，无需下载直接使用。
## 功能需求
多种水印边框模板可选，支持多种相机品牌，支持图片参数自动读取，操作维度丰富(模糊、虚化、阴影、多字体、圆角)
## 技术要点
无损导出，参数可调，批量导出
## 附加要求
免费、高效、无广告、模板更新快
## 用户调研
[摄影圈的程序员，我想开发摄影相关的软件，看看大家的意见](https://tieba.baidu.com/p/9121533645)

# 开发计划
## 边框水印
+ ~~(done)项目搭建与技术选型~~
+ (80%)页面基础布局，左边模板、中间图片预览、右边设置项
+ ~~(done)实现图片预览、导入、导出、Exif信息读取~~
+ ~~模板：背景模糊，前景圆角与阴影，底部显示机型与Exif信息~~
+ 模板：纯色背景，前景圆角与阴影，底部显示机型与Exif信息
+ 模板：原图背景，机型与Exif信息任意位置
## 数字水印
+ 技术预研，实现不可见水印
+ 研究在涂抹、裁剪、截图、转码等处理后的安全性
+ 页面搭建，自定义水印内容，图片加数字水印
+ 数字水印解析
## 用户体系
开发计划视运营情况而定
+ 用户登录、注册
+ 照片广场：分享、点赞、评论
+ 自定义模板：保存、分享、引用

## Star History
[![Star History Chart](https://api.star-history.com/svg?repos=printlin/OnlineImageWatermark&type=Date)](https://star-history.com/#printlin/OnlineImageWatermark&Date)