# 字"姐"跳动，Character dancing！
天秀！字符竟可以如此“性感”. 
本项目 基于飞桨PaddleSeg人像分割实现，让平凡的字符变得“性感” 

 通过 PaddleSeg 完成人像分割，将人像进行分割，将得到的人像作为词云的填充区域进行填充，然后将填充好的人像添加背景，最后完成我们想要的效果。 下面我们一起来看一下整体效果吧:
- 对单张图片的转换，左边是原始图片，通过人像分割，再将人像作为词云的填充区域进行填充，右边就是我们实现的效果：


![show01](https://ai-studio-static-online.cdn.bcebos.com/77f2b87fe9a74fdf912be4146c3aca8c40b8bda27b624ceb9c9b57a273c472d7)

- 在实现单张图片转换之后，我们就可以对视频中的每一帧进行处理，通过视频中的人物运动，让字"姐"动起来!  我b站上找了一个性感的小姐姐进行转换（别只看小姐姐哦！），效果如下：

![show02](https://ai-studio-static-online.cdn.bcebos.com/24b85d2f301d48978ac5139226e3d492c3cdf4092c2e4f1996cd5f2735d4967a)
![show03](https://ai-studio-static-online.cdn.bcebos.com/fea32cd55d034a45bb4e1dd15cf8d59e57d59a54b03b48bfaa2f2ca47b9d137a)

- 观看完整视频请到 https://www.bilibili.com/video/BV1yv41167a9/


具体实现，请查看 https://aistudio.baidu.com/aistudio/projectdetail/1176398
PaddleSeg 课程链接：https://aistudio.baidu.com/aistudio/course/introduce/1767
