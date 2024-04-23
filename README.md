# WangboaoDataMining
数据挖掘大作业      学号:92342210  姓名：王博奥   专业：计算机技术  指导老师：秦静
## 建立库的过程
### 1.进入官网，点击sign up注册。
![image](https://github.com/HuangGuoLii/WangboaoDataMining/assets/76643849/d8b2ee88-4c0e-4a30-9e20-ee692be0bd1a)    


  
### 2.然后输入邮箱注册，由于我已经注册过了，所以直接点击sign in登录即可。
![image](https://github.com/HuangGuoLii/WangboaoDataMining/assets/76643849/515dd845-f9c5-4804-8ad4-bdf47de02652)
### 3.输入账号密码，点击登录。
![image](https://github.com/HuangGuoLii/WangboaoDataMining/assets/76643849/194fbf6c-05e0-4b93-94ab-8d475407fa26)
### 4.点击new，新建仓库，输入库名以及相应描述确认即可。
![image](https://github.com/HuangGuoLii/WangboaoDataMining/assets/76643849/67ab668f-c666-49df-89a0-ea556ca94976)
![image](https://github.com/HuangGuoLii/WangboaoDataMining/assets/76643849/368dcfb4-1951-4860-a0ec-47c750ed5f43)
### 5.建立成功之后，上传文件，将自己的ppt上传至库中，然后编辑readme文件对过程进行描述。
![image](https://github.com/HuangGuoLii/WangboaoDataMining/assets/76643849/8a3ca2e0-ff12-4c09-a833-76c1e0a3f5cf)
### 至此，关于PPT上传过程的描述到此结束。
## 想学习掌握的计算机技能
接下来是最后部分，对我想学习或者获得的计算机技能进行详细描述。
大半年的研究生学习，对专业课的学习，以及与导师和同学直间的交流之后，逐渐对自身研究方向有了较为清晰的认知，以及该学习哪些方面，掌握哪些基本知识有了基本了解。下面我就对我学习这些知识需要掌握的计算机技能做一个总结。
### 学习目标是将事件相机和普通相机结合，利用深度学习识别帕金森病
如果要实现以上目标，我需要先了解事件相机和普通相机的原理；第二呢是先把深度学习基本知识学习，尤其是在医学图像识别中的应用；第三是要研究学习事件相机和普通相机之间的融合方式；第四是要对研究所要用到数据集要有一个认识，该用什么样的数据，是公开数据集还是实验室收集都要做一个清晰的了解；第五步最重要的一步就是对模型的设计和训练，整合所学习的预备知识，在代码中实现出来，再进行评估和优化；最后一步就是对以上知识进行总结，完成毕业要求。然后在下边分别介绍以上六点知识的学习。
### 1.事件相机和普通相机
事件相机一种感光装置，能够以微秒级的时间分辨率捕捉场景中的运动信息，而不需要像传统相机那样以固定频率连续拍摄。这种特性使得事件相机在高速运动场景中具有优势，并且能够更有效地捕捉动态变化。
普通相机是我们常见的相机类型，它以固定的时间间隔捕捉静态图像，主要用于拍摄静态场景和静止对象。
### 2.深度学习基本知识
关于深度学习模型，我应该掌握卷积神经网络（CNN）等深度学习模型的原理和应用，还要了解它们在医学图像识别中的优势和局限性。关于医学图像识别，我应该了解帕金森有关的基本知识，比如说发病原因，发病特征，重要的是发病特征，这对于机器学习诊断至关重要，还要广泛了解深度学习在医学领域的各种应用，包括疾病诊断、病变检测等。
### 3.事件相机和普通相机之间的融合
即多模态的应用，多传感器数据融合理论指出，所要融合的传感器数据应该具有互补性与差异性，否则融合没有太多意义。事件相机与传统相机的数据特性并不相同，二者特征相融合就存在可能。在数据融合方面，研究如何将事件相机和普通相机捕获的信息进行融合，可以获取更全面和准确的场景描述。特征提取，信息融合之后，探索如何从融合后的数据中提取有效的特征，来供深度学习模型使用也同样重要。
### 4.数据集
鉴于实验室的特殊情况，有能力去采集数据组建数据集，这在计算机视觉领域是尤为难得的。在数据收集阶段，应收集包括帕金森病患者和健康人群的事件相机和普通相机图像数据。在数据标注阶段，可能需要专业人士比如此领域的医生对数据进行标注，包括帕金森病的相关特征标注，如手部震颤、步态异常等。
### 5.模型的训练和评估
在模型选择阶段，选择适合任务的深度学习模型结构，可能包括CNN、循环神经网络（RNN）、图神经网络等，对于师兄师姐先前的研究经验，很值得我去深入学习，延续学习；针对所要研究的内容，我应该针对时序类型数据处理的模型进行深入学习；在训练时，要选用合适的训练策略，包括数据增强、迁移学习等，以提高模型的泛化能力和效果。
在模型评估和优化时，要选用合适的评估指标，来评估训练好的模型在帕金森病识别任务上的性能，包括准确率、召回率等指标。模型优化要根据评估结果对模型进行调优和优化，可能涉及超参数调整、模型结构修改等。
### 6.知识总结
对于以上的知识学习规划，肯定是不能短时间内学得的，我应该一步一脚印，从最基本的领域知识学起，逐渐掌握更深层次的知识，将之融合在一起。在模型学习过程中，我不能够只看理论，更要注重实践，尤其是模型代码的学习，导师教给我们的多注重项目的实践都是对前人经验的总结，很值得我去学习。
#### 以上一部分就是我对未来我需要学习的一个知识（计算机技能）做的一个概述，希望能够通过这种方式提醒自己，始终走在规划的道路上，省去一些不必要的学习。




