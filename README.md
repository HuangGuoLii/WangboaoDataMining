## WangboaoDataMining  数据挖掘大作业
### 姓名：王博奥   学号:92342210   专业：计算机技术   指导老师：秦静
## 一、建立库的过程
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
---------------------------
## 二、想学习掌握的计算机技能
接下来这一部分，是对我想学习或者获得的计算机技能进行详细描述。
大半年的研究生学习，对专业课的学习，以及与导师和同学直间的交流之后，逐渐对自身研究方向有了较为清晰的认知，以及该学习哪些方面，掌握哪些基本知识有了基本了解。下面我就对我学习这些知识需要掌握的计算机技能做一个总结。
### 学习目标是将事件相机和普通相机结合，利用深度学习识别帕金森病
如果要实现以上目标，我需要先了解事件相机和普通相机的原理；第二呢是先把深度学习基本知识学习，尤其是在医学图像识别中的应用；第三是要研究学习事件相机和普通相机之间的融合方式；第四是要对研究所要用到数据集要有一个认识，该用什么样的数据，是公开数据集还是实验室收集都要做一个清晰的了解；第五步最重要的一步就是对模型的设计和训练，整合所学习的预备知识，在代码中实现出来，再进行评估和优化；最后一步就是对以上知识进行总结，完成毕业要求，也是对自己所学知识的一个检验和总结。  

然后我会在下边分别介绍以上六点知识的学习。
### 1.事件相机和普通相机
事件相机是一种感光装置，其关键特点是能够以微秒级的时间分辨率捕捉场景中的运动信息。与传统相机不同，事件相机不需要以固定频率连续拍摄，而是仅在场景发生变化时才记录图像数据。这种特性使得事件相机在高速运动场景中具有明显的优势，能够更精准地捕捉动态变化，而不会出现运动模糊或漏捕情况。   

相比之下，普通相机以固定的时间间隔捕捉静态图像，主要用于拍摄静态场景和静止对象。因此，事件相机和普通相机在应用场景和工作原理上存在明显差异，各自具有独特的优势和适用范围。
### 2.深度学习基本知识
关于深度学习模型，对我来说去掌握卷积神经网络（CNN）等深度学习模型的原理和应用是至关重要的。对于医学图像识别，除了了解帕金森病的基本知识，如发病原因和特征外，尤其重要的是深入了解帕金森病在图像上的特征表现。这些特征可能包括运动异常、姿势不稳、手部震颤等，对这些特征的准确识别对于机器学习诊断至关重要。   

此外，对深度学习在医学领域的应用也应有广泛了解，涵盖疾病诊断、病变检测等各种方面。深度学习在医学图像识别中的优势包括对大规模数据的处理能力和高度自动化的特点，但也存在一些局限性，如对数据质量要求较高、模型解释性不足等。因此，我要去综合掌握深度学习模型原理、医学图像特征和应用场景是进行医学图像识别研究和应用的关键。
### 3.事件相机和普通相机之间的融合
事件相机与普通相机之间的融合，涉及到多模态的应用和多传感器数据融合。传感器数据的融合应具备互补性与差异性，以确保融合具有实际意义。由于事件相机和传统相机的数据特性不同，它们的特征相融合具有潜在的可能性。在数据融合方面，研究如何有效地将事件相机和普通相机捕获的信息进行融合，有助于获得更加全面和准确的场景描述。   

在特征提取和信息融合后，进一步探索如何从融合后的数据中提取有效的特征，以供深度学习模型使用，也是至关重要的。这样的融合方法有助于克服传统相机在高速动态场景中可能出现的运动模糊和漏捕等问题，从而提高图像识别和分析的准确性和鲁棒性。
### 4.数据集
考虑到实验室的独特条件，能够采集数据并建立数据集是在此领域中非常难得的机会。在数据收集阶段，应该全面收集帕金森病患者和健康人群的事件相机和普通相机图像数据，以确保数据集的多样性和代表性。数据的多样性将有助于模型在不同场景和条件下的泛化能力。在数据标注阶段，可能需要专业人士，如医生或专业研究人员，对数据进行标注。   

这些标注应该包括帕金森病的相关特征，例如手部震颤、步态异常等，以便为深度学习模型提供准确的训练和评估标准。确保数据的准确标注是构建高质量数据集和有效训练模型的关键步骤之一，因为标注质量直接影响着模型的性能和泛化能力。
### 5.模型的训练和评估
在模型选择阶段，应该根据任务的特点选择适合的深度学习模型结构，可能涉及到CNN、RNN、图神经网络等不同类型的模型。借鉴师兄师姐们先前的研究经验是一个很好的起点，这有助于我深入学习并延续他们的研究方向。考虑到研究内容涉及时序类型数据处理，我将重点学习和探索针对这种数据类型的深度学习模型。   

在训练阶段，选择合适的训练策略至关重要，其中包括数据增强和迁移学习等技术，这有助于提高模型的泛化能力和性能效果。   

在模型评估和优化阶段，应该选择适当的评估指标来衡量模型在帕金森病识别任务上的性能，如准确率、召回率等指标。根据评估结果，对模型进行调优和优化，可能涉及超参数调整、模型结构修改等操作，以不断提升模型的性能和效果。
### 6.知识总结
对于上述知识学习规划，我清楚地认识到这并非一朝一夕的事情。为了在这个过程中不断进步，我应该脚踏实地，从最基本的领域知识入手，逐渐掌握更深层次的知识，然后将这些知识融会贯通。在这个过程中，我不仅要掌握理论知识，还需要注重实际应用，特别是深入学习模型的代码。这种实践能力的培养非常重要，因为它不仅可以帮助我理解理论知识在实际项目中的应用，还可以通过实践不断完善我的技能。   

导师们强调实践的重要性，这是一种非常宝贵的经验，他们的建议是基于多年来对项目的实际操作总结出来的。实践中遇到的问题和挑战可以帮助我更好地理解理论知识，同时锻炼我的问题解决能力。因此，我会将理论学习与实际操作相结合，通过实际项目的经验，不断积累和提升我的技能和知识水平。这种学习方法不仅能够提高我的能力，还能帮助我更好地适应未来的工作和研究。
#### 总结
这个概述不仅仅是对我的学习需求的总结，更是一种对未来发展方向的自我激励。它能够让我意识到学习是一个渐进的过程，需要持之以恒地坚持下去，而不是一蹴而就。通过将我的学习目标和计划清晰地表达出来，我可以更好地为自己设定目标，并且在学习的过程中时刻提醒自己要朝着这些目标努力前行。   

通过这一个概述作为我学习过程中的一个参考框架，帮助我更好地组织学习内容，确保我不会遗漏重要的知识点。同时，它还可以作为我未来学习过程中的一个反馈机制，让我随时检查自己的学习进度，及时调整学习策略。
总的来说呢，通过这种方式，我可以更加有序地进行学习，提高学习的效率和质量，从而更好地实现我的学习目标和职业发展规划。




