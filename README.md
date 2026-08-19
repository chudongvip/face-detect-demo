

# 前端“易容术”

上一个 DEMO，我介绍了前端的图像处理技术，没有看过的朋友可以先看这个[项目](https://github.com/chudongvip/process_image_demo)，项目同样是分多个 DEMO ，按照 DEMO 的顺序我相信你很快就会入门的。

由于个人兴趣，一直想研究一下人工智能，从事前端工作关于 AI 的使用几乎为零，在我年计划中显然成为了老赖，于是乘热打铁，卯足干劲，一个人“前端换脸的概念”的想法出现了，因此就有了以下的一个两个三个... DEMO。

本文适合没有接触过或有兴趣接触的朋友，当然还有图像处理技术的入门，可谓是一石二鸟，不可多得的好项目（王婆卖瓜一波😛）。

先来一张效果图

![一张效果图](./effect-picture/multi-detect.gif)

推荐 DEMO 路线，召唤师请跟随我！

- `index.html`

  图片处理，使用 canvas 绘制原图，然后通过人脸识别检测到眼睛的位置，在眼睛的位置添加上小 ♥️

  ![一张效果图](./effect-picture/pic-add-red-heart.png)

- `play-video-in-canvas.html`

  在 `canvas` 中播放实时采集的本地视频头，目的是为了拿到自己在视频头中的每一帧（一张图片），这样就可以通过人脸识别技术获取到自己实时的人脸信息。

- `detect-video.html`

  > 我们可以检测 mp4 等视频中的人脸

  视频处理，通过人脸识别技术获取到视频每一帧（图片）中是否有人脸以及人脸五官的位置，然后在添加相对应的贴图。

  ![检测视频中的眼睛](./effect-picture/detect-video-eyes.gif)

- `detect-camera.html`

  `play-video-in-canvas.html` 就是这个 DEMO 的铺垫，拿到了本地人脸信息，我就可以“为所欲为”了。

  ![一张效果图](./effect-picture/single-detect-with-things.gif)


## 相关链接

- [一篇前端图像处理秘籍](https://github.com/chudongvip/process_image_demo)

- [TensorFlow JavaScript 模型](https://tensorflow.google.cn/js/models)

- [Blazeface detector](https://github.com/tensorflow/tfjs-models/tree/master/blazeface)
