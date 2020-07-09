# 3D人脸重建，生成不同面部表情

> 在 [Deep3DFaceReconstruction](https://github.com/microsoft/Deep3DFaceReconstruction) 基础上进行不同表情重建。

## Code

在将来的某个时候开源代码。

## Results

### 渲染部分

![img](results/input.png)

![img](results/output.png)

### 重建部分

* 原始图像

![](input/000007.jpg)

* 原始重建效果：

  ![](results/000007_mesh00.png)

#### 尝试了四种概率生成方式，gif显示如下：

![](./results/demo_softmax.gif)![](./results/demo_softplusmax.gif)

![](./results/demo_smoothmaxL1.gif)![](./results/demo_smoothmaxL2.gif)



#### softmax概率生成方式（跟上面gif使用的模型不是同一数据集训练的）

* 生成表情Surprise

![](results/surprise.png)

* 生成表情Happy

![](results/happy.png)

