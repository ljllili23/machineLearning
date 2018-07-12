# Gram矩阵

 

**在图像内容附近通过白噪声初始化一个输出的结果，然后通过网络对这个结果进行风格和内容两方面的约束进行修正。而在风格的表示中采用的是Gram Matrix。**

**我是这样理解为什么用Gram 矩阵的：度量各个维度自己的特性以及各个维度之间的关系。**

  style transfer 当中，什么是风格，存在自己特性的才叫做风格。因此如何去度量这个自己的特性勒，自己的特点越突出，别人的越不突出最好。因此论文当中这样去做：

<img src="https://pic2.zhimg.com/v2-4d4bd3dd55fe50fb366bbf3d31ce3dbd_b.png" data-rawwidth="202" data-rawheight="65" class="content_image" width="202">![img](https://pic2.zhimg.com/80/v2-4d4bd3dd55fe50fb366bbf3d31ce3dbd_hd.png)

 

<img src="https://pic4.zhimg.com/v2-b72ead36f2277ff9032a9f6b43faa633_b.png" data-rawwidth="489" data-rawheight="120" class="origin_image zh-lightbox-thumb" width="489" data-original="https://pic4.zhimg.com/v2-b72ead36f2277ff9032a9f6b43faa633_r.jpg">![img](https://pic4.zhimg.com/80/v2-b72ead36f2277ff9032a9f6b43faa633_hd.png)

 

# 感知机学习算法的对偶形式

![img](https://pic3.zhimg.com/80/v2-974ea3af04429260846227e192d9c78e_hd.png)

