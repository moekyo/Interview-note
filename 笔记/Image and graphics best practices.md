# Image and graphics best practices

显示图片所占用的内存和图片大小无关，而和图片的分辨有关。



[Image Resizing Techniques](https://nshipster.com/image-resizing/)

## 使用下采样技术对图片进行压缩，可以大量地减少内存占用

## 列表滚动时的图片解码

* 预加载数据    [A tour of UICollectionView](https://developer.apple.com/videos/play/wwdc2018/225/)
* 后台解码/下采样
* ![Snipaste_2021-03-05_19-20-13](C:\Users\moekyo\Desktop\笔记\Image and graphics best practices.assets\Snipaste_2021-03-05_19-20-13.png)

## 多使用预置图片素材（Image Assets）

* 针对基于名称和特征的查找进行了优化
* 更加智能的缓存区管理
* 针对不同设备的瘦身功能
* 矢量图片支持

## 使用 UIGraphicsImageRenderer 进行图片绘制

## 总结

![image-20210305194117402](C:\Users\moekyo\Desktop\笔记\Image and graphics best practices.assets\image-20210305194117402.png)