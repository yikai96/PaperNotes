# Online Multi-Target Tracking Using Recurrent Neural Networks
|               | Online Multi-Target Tracking Using Recurrent Neural Networks |
| ------------- | -------------            |
| Writer | Anton Milan et al. The University of Adelaide |
| Publication | AAAI 2017 |
| Citation | 4 until 20170215  |
| Reading Time | Feb 15th, 2017  |
| Field | Online Multi-Object Tracking, Tracking by Detection |  
| Challenge | Data association under occlusion and noisy detections |
| Contributions | Utilize Decision Making for MOT(MDPS)|

-----------------------------
# 论文摘要
我们提出了基于循环神经网络的在线多目标追踪的新方法。在真实场景下的多目标追踪涉及到许多的挑战，包括a). 一个先验未知并且数目随时间变化的目标；b). 连续不断地对当前的目标进行状态评估；c). 数据关联的离散结合问题。在解决这些问题上，大部分之前的方法都需要对变量进行繁琐的调整。在这篇论文中，我们第一次提出了应用于在线多目标追踪的端对端学习方法。现存的深度学习方法并不是为解决上述的挑战而设计的，因此其不能够不加修改地应用于挑战的解决之上。我们的方案利用了卷积神经网络的相关原理加以修正来解决上述问题。在约为300HZ标准GPU上我们基于理论以及真实数据的实验显示了方法的可观效果，同时，在讲深度学习应用于多目标追踪上开辟了新道路。

------------------------
# 总体思路
