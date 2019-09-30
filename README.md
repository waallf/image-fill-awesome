# image-fill-awesome
图像修复  

[Deep fill](http://jiahuiyu.com/deepfill/)  
[Deep fill V2](http://jiahuiyu.com/deepfill2/)  
[edge_connect](https://arxiv.org/pdf/1901.00212v3.pdf)  
[water_detection](http://openaccess.thecvf.com/content_cvpr_2017/papers/Dekel_On_the_Effectiveness_CVPR_2017_paper.pdf)  
[LearningPyramid-ContextEncoderNetworkforHigh-QualityImageInpainting](https://arxiv.org/pdf/1904.07475v4.pdf)  
[CoherentSemanticAttentionforImageInpainting](https://arxiv.org/pdf/1905.12384v3.pdf)  
[Copy-and-PasteNetworksforDeepVideoInpainting](https://arxiv.org/pdf/1908.11587v1.pdf)  


生成图像得评价指标:  
l1损失  
SSIM(structural similarity index): [参考链接](https://blog.csdn.net/u014260892/article/details/44344091)  
PSNR(峰值性躁比):  
IS(inception score): 思想：质量越好的图像约容易进行分类，所以使用训练好的网络进行提取特征并分类，某一类的概率越大则表明该图像质量越好。最终使用预测概率与样本概率求交叉熵作为指标。 [参考链接](https://blog.csdn.net/qq_27261889/article/details/86483505)  
FID (Fr´echet Inception Distance):  
相同的inception network来提取中间层的特征。然后我们使用一个均值、方差为计算。  
[参考链接](https://blog.csdn.net/qq_27261889/article/details/86483505)  
