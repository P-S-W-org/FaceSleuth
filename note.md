# 开发笔记

人脸识别的过程中有4个关键的步骤：

1. 人脸检测：寻找图片中人脸的位置
2. 人脸对齐：将不同角度的人脸图像对齐成同一种标准的形状
3. 人脸编码：将人脸图像的像素值转换成紧凑且可判别的特征向量（temple）
4. 人脸匹配：比较模板，得到一个相似度分数

## 相关实践资料

[人脸相关算法、数据集、文献资源大列表](https://mp.weixin.qq.com/s/L1APIqWF8nqI1RnZXTNtiw)

[人脸识别的简要介绍（附实例、Python代码）](https://www.jiqizhixin.com/articles/2018-11-05-20?from=synced&keyword=人脸识别)

[深度人脸识别中不同损失函数的性能对比](https://www.jiqizhixin.com/articles/2019-02-07-5?from=synced&keyword=人脸识别)