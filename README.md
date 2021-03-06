# MagicCamera介绍
MagicCamera是一个美颜相机，目前主要介绍美颜相机的实现。UI暂时还未细化，后面会抽空整合。

**大致功能如下**
* 实时美颜、美白
* 人脸特效(2D 动态贴纸)
* 美妆 (大眼、瘦脸、唇彩等)
* 风格滤镜
* 断点拍摄、断点回删 
* 视频编辑

**已经实现的部分**
* 人脸关键点识别
* 实时美颜、美白
* 人脸特效(2D 动态贴纸)
* 美妆 (大眼、瘦脸、唇彩)
* 风格滤镜
* 断点拍摄、断点回删

# 备注：
注意事项：关于人脸关键点SDK验证问题，由于采用Face++的试用版作为测试的，每天使用的次数有限，所以这里建议大家到Face++官网([https://www.faceplusplus.com/](https://www.faceplusplus.com/))(提示:切换中文官网速度比较快) 注册一个Key使用。项目中有提供了两个测试Key(Face-SDK/MGLicenseManagerHelper/MGNetAccount.h)，可能会验证失败，大家可以自行替换。

# 效果图:
## 动态贴纸
<img src="https://github.com/ymkil/MagicCamera/blob/master/image/sticker_01.png" width="200" /> <img src="https://github.com/ymkil/MagicCamera/blob/master/image/sticker_02.png" width="200" />
