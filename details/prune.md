# ✂️ 剪枝
<details>
<summary>

## Part 1 - 基础快速入门 (100%)

</summary>

1. 剪枝引言
2. 非结构-细粒度剪枝上
3. 非结构-细粒度剪枝下
4. 非结构-向量剪枝
5. 卷积核剪枝
6. 结构化剪枝【可视化】
7. 结构化剪枝【可视化】
8. 修剪标准-基于权重大小与梯度大小上
9. 修剪标准-基于权重大小与梯度大小下
10. 抱歉没有3这个文件的出现仅仅是为了与jupyter目录对齐
11. 两个剪枝框架的简单了解
12. dropout_and_dropconnect【额外】
13. removing剪枝-训练部分
14. removing剪枝【剪枝与微调部分】
15. 参数量计算与稀疏训练的引入
16. 稀疏训练经典baseline手写复现
17. pytorch调包-自己用钩子函数进行剪枝
18. pytorch调包-inspect模块内部的数据流转
19. pytorch调包-序列化剪枝模型与全局剪枝
20. pytorch调包-自定义prune函数

</details>

<details>
<summary>

## Part 2 - 基于VGG的模型剪枝 (100%)

</summary>


21. 章节介绍
22. CIFAR10数据集
23. VGG网络搭建
24. BatchNorm
25. L1&L2正则概念
26. train-parse_opt
27. train-train
28. trainsave_checkpoint-test
29. train3.5.train
30. Pruning-Intro
31. Pruning-完整流程演示
32. Prune-3个层的剪枝
33. Prune-test()
34. Prune-加载稀疏训练模型
35. Prune-前处理
36. Prune-建立新模型并存储信息
37. Prune-BatchNorm层的剪枝
38. Prune-Conv2d层的剪枝
39. Prune-Conv2d层的剪枝

</details>

<details>
<summary>

## Part 3 - 英伟达2-4剪枝方案 (100%)

</summary>


40. nvida剪枝方案-通用稀疏方案简介
41. nvida剪枝方案-图解nvidia2-4稀疏方案
42. nvida剪枝方案-针对不同网络的训练策略
43. nvida_2-4剪枝-手写复现概览
44. nvida_2-4剪枝-ASP类的实现
45. compute_mask函数实
46. m4n2的实现上
47. m4n2的实现下
48. 剪枝中如何初始化模型上
49. 剪枝中如何初始化模型下
50. 剪枝中如何给layer嵌入稀疏特性
51. 剪枝中如何初始化optimizer

</details>

<details>
<summary>

## Part 4 - Yolov8pruning: TB-conv 剪枝方案（全网首推）(100%)

</summary>

52. yolov8剪枝overview
53. pretrain[非必要]
54. 约束训练和TB剪枝初探
55. onnx分析剪枝Bottleneck,C2f,SPPF
56. 最小剪枝Conv单元的TopConv
57. 最小剪枝Conv单元的BottomConv
58. Seq剪枝
59. Seq剪枝补充
60. Detect-FPN剪枝
61. yolov8剪枝总结

</details>

## Part 5 - 重参【正在更新】
