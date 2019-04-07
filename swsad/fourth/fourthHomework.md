# fourthHomework

1、简答题

1. 用例的概念

    >A use case is a list of actions or event steps typically defining the interactions between a role (known in the Unified Modeling Language (UML) as an actor) and a system to achieve a goal. 
    
    一个用例定义了用户角色和系统为了达成某个目标所进行的交互，包括一系列动作和事件步骤。
    

2. 用例和场景的关系？什么是主场景或 happy path？

    >- A use case represents a collection of scenarios: primary,plus zero or more alternates.
    >  - The primary scenario（主场景／基本流）corresponds tothe main system interactions, usually the ‘success’ scenario.最常用，直接地实现用户目标的故事
    >- Alternate scenarios（可选场景／备选流）correspond toless    frequent    interactions    and    exceptions.在实现用户目标过程中较少适用与意外故事
    
3. 用例有哪些形式？

    三种格式 Brief, Casual, Fully
    - Brief (high level)
        - Terse one-paragraphsummary, usually of the main successscenario.
        - Duringearly requirements analysis, to get a quick sense of subjectand scope. May take only a few minutes to create.
    - Casual (简便格式)
        - Informal paragraph format. Multiple paragraphs that cover variousscenarios.
        - When? As above.
    - Fully
        - dressed All steps and variations are written in detail, and there aresupporting sections, such as preconditions and success guarantees.
        - After many use cases have been identified and written in a briefformat,then during the first requirements workshop a few (suchas 10%)of thearchitecturally significantandhigh-value usecasesare written in detail.
    
4. 对于复杂业务，为什么编制完整用例非常难？

    业务复杂，场景多，变化多，难以覆盖
    
5. 什么是用例图？

    > Use case diagram is an excellent pictureof the system context; 
    >- It makes a good context diagram,
    >- Showing the boundary of a system, what lies outside of it, and how it gets used. 
    >- It serves as a communication tool that summarizes the behavior of a system and its actors.

6. 用例图的基本符号与元素？
    用例图包6个元素，参与者，用例，关联关系，包含关系，扩展关系，泛化关系。

7. 用例图的画法与步骤

    - 确定参与者
    
        （1）谁将使用该系统的主要功能。  
        
        （2）谁将需要该系统的支持以完成其工作。 

        （3）谁将需要维护、管理该系统，以及保持该系统处于工作状态。  

        （4）系统需要处理哪些硬件设备。  

        （5）与该系统那个交互的是什么系统。 
        
        （6）谁或什么系统对本系统产生的结果感兴趣。
    - 识别用例 从分析系统的参与者开始，考虑每一个参与者是如何使用系统的。
    - 识别用例间的关系

8. 用例图给利益相关人与开发者的价值有哪些？

    > Use case diagram is an excellent pictureof the system context; 
    >- It makes a good context diagram,
    >- Showing the boundary of a system, what lies outside of it, and how it gets used. 
    >- It serves as a communication tool that summarizes the behavior of a system and its actors.
2、建模练习题（用例模型）

* 选择2-3个你熟悉的类似业务的在线服务系统（或移动 APP），如定旅馆（携程、去哪儿等）、定电影票、背单词APP等，分别绘制它们用例图。并满足以下要求：
    - 请使用用户的视角，描述用户目标或系统提供的服务
    - 粒度达到子用例级别，并用 include 和 exclude 关联它们
    - 请用色彩标注出你认为创新（区别于竞争对手的）用例或子用例
    - 尽可能识别外部系统和服务
* 然后，回答下列问题：
    1. 为什么相似系统的用例图是相似的？
    2. 如果是定旅馆业务，请对比 Asg_RH 用例图，简述如何利用不同时代、不同地区产品的用例图，展现、突出创新业务和技术
    3. 如何利用用例图定位创新思路（业务创新、或技术创新、或商业模式创新）在系统中的作用 
    4. 请使用 SCRUM 方法，选择一个用例图，编制某定旅馆开发的需求（backlog）开发计划表 
    5. 根据任务4，参考 [使用用例点估算软件成本](https://www.ibm.com/developerworks/cn/rational/edge/09/mar09/collaris_dekker/index.html)，给出项目用例点的估算


