# zhouxy.github.io
# 系统分析与设计第一次作业
## 1.软件工程的定义

(1) 将系统化、规范化、可度量的方法应用与软件的开发、运行和维护-的过程，即将工程化应用于软件中。  
(2) 对(1)中所述方法的研究。  
软件工程知识体系:

以高质量为目标，研究软件生产的过程模型、方法和工具
## 2.解释导致 software crisis 本质原因、表现，述说克服软件危机的方法

软件危机（Software Crisis）是一个早期的计算机科学用语，指的是在给定时间内编写出可用和高效的程序的困难性。现在引申至指软件在开发和维护过程中出现的一系列严重的问题。
在1972年，Edsger Dijkstra 指出计算能力约强大，编程越是大问题。因此导致软件危机的本质原因是计算机计算能力的迅速增长，以及计算机能力增长而导致软件需要处理和解决的问题具有更大的复杂性。也就是计算机计算能力的提高超过了程序员能够高效利用计算机的能力。
软件危机的主要表现有：

进行了超预算的项目
项目长期无法完成
软件非常低效
软件质量低下
软件经常与用户的需求不匹配
项目难以管理
程序代码的后期维护存在困难
软件无法完成并交付
## 3.软件生命周期

软件生命周期（Software Development LifeCycle）是指软件的产生直到成熟的全部过程。早期的软件生命周期受到瀑布模型的影响，因此通常定义为：

软件从计划、需求开始，经历分析设计、实现、部署、维护，直到最后逐渐消亡的。
因此，现在对软件生命周期及软件生命周期模型采用如下定义：

软件生命周期是指软件的产生直到成熟的全部过程。
软件生命周期模型是指人们为开发更好的软件而归纳总结的软件生命周期的典型实践参考。
根据GB/T 8567的定义，软件生命周期分为以下6个阶段：

可行性分析与计划
需求分析
设计（概要设计和详细设计）
编码实现
测试
运行和维护
常见的软件生命周期模型有原型模型、螺旋模型、迭代模型。

## 4.SWEBoK 的 15 个知识域（An Overview of the SWEBOK Guide 请中文翻译其名称与简短说明）

SWEBOK V3中的15个知识域包括：

11个软件工程实践知识域：

软件需求 Software requirements
真实世界问题而必须展示的特性。软件需求的知识域包括七个子域，即软件需求基础、需求过程、需求获取、需求分析、需求规格说明、需求确认和实践考虑。
软件设计 Software design
根据IEEE [ IEEE 610.12-90] ，设计既是"定义一个系统或组件的体系结构、组件、接口和其他特征的过程"，又是"这个过程的结果"。软件设计的知识域包括六个子域，即软件设计基础、软件设计关键问题、软件结构与体系结构、软件设计质量的分析与评价、软件设计符号、软件设计的策略与方法。
软件构造 Software construction
它指通过编码、验证、单元测试、集成测试和排错的组合，具体创建一个可以工作的、有意义的软件，其知识域包括软件构造基础、管理构造、实际考虑三个子域。
软件测试 Software testing
它是由在有限测试用例集合上，根据期望的行为，对程序的行为进行的动态验证组成， 测试用倒是实际上无限的执行域中适当选择出来的。软件测试包括五个子域，即软件测试基础和测试级别、测试技术、需求分析、与测试相关的度量、测试过程。
软件维护 Software maintenance
软件一旦投入运行，就可能出现异常，运行环境可能发生改变，用户会提出新的需求。生命周期软件维护阶段从软件交付时开始，但是维护活动出现得还要早。软件维护的知识域包括四个子域，即软件维护基础、软件维护的关键问题、维护过程、维护技术。
软件配置管理 Software configuration management
为了系统地控制配置的变更和维护在整个系统生命周期中的完整性和可追踪性，而标志软件在时间上不同点的配置的学科。软件配置管理包括六个子域，即软件配置管理过程管理、软件配置标志、软件配置控制、软件配置状态统计、软件配置审核、软件发行管理和交付。
软件工程管理 Software engineering management
处理软件工程的管理与度量，虽然度量是所有知识域的一个重要方面，但是这里涉及的是度量程序的专题。软件工程管理包括六个子域，即启动和范围定义、软件项目计划、软件项目实施、评审与评价、关闭、软件工程度量。前五个覆盖软件过程工程 管理，第六个描述软件度量的程序。
软件工程过程 Software engineering process
涉及软件工程过程本身的定义、实现、评定、度量、管理、变更和改进。软件工程过程包括四个子域，即过程实施与改变、过程定义、过程评定、过程和产品度量。
软件工程模型和方法 Software engineering models and methods
包括软件工程工具、软件工程方法两个子域。
软件质量 Software quality
处理跨越软件生命周期过程的软件质量的考虑，由于软件质量在软件工程中元处不在，其他知识域也涉及质量 问 题。软件质量包括三个子域，即软件质量基础、软件质量过程、实践考虑。
软件工程职业实践 Software engineering professional practice
4个软件工程教育基础知识域：

软件工程经济学 Software engineering economics
计算基础 Computing foundations
数学基础 Mathematical foundations
工程基础 Engineering foundations
## 5.简单解释 CMMI 的五个级别。例如：Level 1 - Initial：无序，自发生产模式。

能力成熟度模型集成（英语：Capability Maturity Model Integration，简称CMMI或“希迈”）是一种改进过程的方法，其目的是协助提升组织的绩效。

Level 1 - Initial：初始级。

软件过程是无序的，有时甚至是混乱的，对过程几乎没有定义，成功取决于个人努力。管理是反应式的。

Level 2 - Managed：可管理级。

建立了基本的项目管理过程来跟踪费用、进度和功能特性。制定了必要的过程纪律，能重复早先类似应用项目取得的成功经验。

Level 3 - Defined：已定义级。

已将软件管理和工程两方面的过程文档化、标准化，并综合成该组织的标准软件过程。所有项目均使用经批准、剪裁的标准软件过程来开发和维护软件，软件产品的生产在整个软件过程是可见的。

Level 4 - Quantitatively Managed：量化管理级。

分析对软件过程和产品质量的详细度量数据，对软件过程和产品都有定量的理解与控制。管理有一个做出结论的客观依据，管理能够在定量的范围内预测性能。

Level 5 - Optimizing：优化管理级。

过程的量化反馈和先进的新思想、新技术促使过程持续不断改进。

## 6.用自己语言简述 SWEBok 或 CMMI （约200字）

SWEBok即软件工程知识体系指南（Guide to the Software Engineering Body of Knowledge)，是一个得到普遍认可的共识性软件工程本体知识结构。（其历史可追溯到1999年4月由发表的《软件工程知识本体结构》报告。报告的发布使人们达成了共识，即建立软件工程本体知识结构是解决如何验证软件工程工程师的资格、如何设置并检验软件工程相关课程等难题的答案。）SWEBok的目的是为软件工程学科的范围提供一致的认识，为支持该学科的本体知识提供指导。SWEBOK V3将软件工程学科的本体知识分为15个知识域，并对每个知识域中的重要概念和区别加以阐述说明。也就是说，SWEBok最大的贡献是将原本混杂的软件工程知识体系化，将原本存在的知识分类整理，最后形成一个具有共识性和方向性的指南。
