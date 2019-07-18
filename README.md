#2D-3D 高清图像2D转3D构思
   [Deep3d ECCV2018](http://arxiv.org/pdf/1604.03650.pdf)这篇文章提出来将2D高清电影转成3D高清电影,核心思想是
先对不同尺度的高清图像进行Encode,之后估计在不同尺度下的深度.然后基于估计的深度将原图合成为stero的另一副高清图像
将估计好的深度和高清图像按照一定的约束,平移到另一副高清图像.
    ##思路
    ###1.高清图像处理 (high resolution image processing)
    将高清图像编码成深度图.这项工作最近有做高清图像-深度图如[Revisiting Single Image Depth Estimation:Toward Higher Resolution map with Accurate Object Boundaries](https://arxiv.org/pdf/1803.08673.pdf)
这项工作直接将高清图像转成高清深度图.有些文章是在别的领域进行High-Resolution如高清图像语义分割中ICNet[Real-Time Semantic Segmentation on high-resolution images](https://arxiv.org/pdf/1704.08545.pdf)

