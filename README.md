# Multi-label-classification
项目描述：在日常生活中一个图片中可能会包含很多的信息，也有可能有不同的分类，这 个项目的目的就是想解决图片的多标签分类问题。 
项目内容 1. 这个项目是基于 PyTorch 进行代码的编写。首先对数据进行预处理，我们得到了图片以及对 于的标签。因为是多标签分类问题，所有对标签使用的是 one-hot 编码，
这样可以体现出一个图片属 于不同标签的信息。对图片预处理使用的是 transforms 包，具体操作分别是修改图片的大小，进行标 准化。 2. 使用的训练模型是 ResNet50 模型，
选择 ResNet 模型原因是相比于 AlexNet，它的准确率 有明显的的提升，而对于 GoogleNet，它的参数不会太大。
