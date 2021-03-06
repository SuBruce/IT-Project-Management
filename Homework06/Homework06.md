## Homework06：项目时间管理

### 题目1：教材练习题6  

![习题6](https://github.com/SuBruce/IT-Project-Management/blob/master/Homework06/images/01.png)   

### (a)双代号网络图  

![习题6-双代号网络图](https://github.com/SuBruce/IT-Project-Management/blob/master/Homework06/images/02.png)    

### (b)路径与长度  

|序号|路径|长度|
|:---|:---|:---|
|1|A-B-E-H-K|2+2+2+2+2=10|
|2|A-B-E-I-J-K|2+2+2+5+1+2=14|
|3|A-C-F-H-K|2+3+3+2+2=12|
|4|A-C-F-I-J-K|2+3+3+5+1+2=16|
|5|A-D-G-J-K|2+4+6+1+2=15|  

### (c)关键路径与长度  

关键路径即最长路径为路径4：**A-C-F-I-J-K**，长度为**2+3+3+5+1+2=16**  

### (d)最短时间  

完成该项目所需的最短时间为关键路径的完成时间，即为**16天**。  

<br/>

### 题目2：教材练习题7   

![习题7](https://github.com/SuBruce/IT-Project-Management/blob/master/Homework06/images/03.png)  

### (a)双代号网络图    

![习题7-双代号网络图](https://github.com/SuBruce/IT-Project-Management/blob/master/Homework06/images/04.png) 

关键路径：**A-D-F-G-I-K-L**，长度为**48**

|任务|总时差|自由时差|
|:---:|:---:|:---:|
|A|0|0|
|B|2|2|
|C|12|12|
|D|0|0|
|E|6|6|
|F|0|0|
|G|0|0|
|H|2|2|
|I|0|0|
|J|12|12|
|K|0|0|
|L|0|0|

- 自由时差 = 所有紧后任务的最早开始时间 - 该任务的最早完成时间
- 总时差 = 最晚开始时间 - 最早开始时间 = 最晚完成时间 - 最早完成时间  

### (b)任务进度表

![习题7-任务进度表](https://github.com/SuBruce/IT-Project-Management/blob/master/Homework06/images/05.png)  

- 任务进度表：一个表格，展示了任务的名称、标号等，其中的信息有：
  - 标识号：任务、 资源或工作分配的创建的顺序。
  - 任务名称：即任务的名称。
  - 工期：任务的工期，即开展活动的实际时间加上根据外部信息留出的一些额外时间。
  - 开始时间：即任务开始的时间。
  - 完成时间：即任务完成的时间。
  - 前置任务：任务的前置任务。只有当一个或多个前置任务已被完成后，该任务才能开始执行。
  - 资源名称：即任务所需资源。
  - 完成度：即任务完成的进度。  

### (c)甘特图  
 
![习题7-甘特图](https://github.com/SuBruce/IT-Project-Management/blob/master/Homework06/images/06.png)  

- 甘特图：甘特图（Gantt chart），又称为横道图、条状图。其通过条状图来显示项目，进度，和其他时间相关的系统进展的内在关系随着时间进展的情况。图表中的条表示任务进度表中对应的任务持续的时间，图标上方的日期是任务的开始和进行日期，图中的箭头表示任务之间的关系，由某任务的前置任务指向该任务，表示其完成顺序。  

### (d)网络图  

![习题7-网络图](https://github.com/SuBruce/IT-Project-Management/blob/master/Homework06/images/07.png)  

- 网络图：网络图(Network planning)，是一种图解模型，形状如同网络，故称为网络图。网络图是由作业（箭线）、事件（又称节点）和路线三个因素组成的。上图的每一个框表示一个活动，框内有活动的开始日期、结束日期和工期等数据。图中的箭线符号表示相关活动之间的顺序。图中的红色部分表示关键路径，它是所有路径中活动工期之和最大的路径，决定了整个项目的最短完成时间。  

<br/>

### 题目3：收集网上资料，总结看板在软件项目中的使用  

### (a)基本概念

- 看板：表示出某工序何时需要何数量的某种物料的卡片，又称为传票卡，是传递信号的工具。看板分两种，即传送看板和生产看板。传送看板用于指挥零件在前后两道工序之间移动。当放置零件的容器从上道工序的出口存放处运到下道工序的入口存放处时，传送看板就附在容器上。当下道工序开始使用其入口存放处容器中的零件时，传送看板就被取下，放在看板盒中。

- 看板管理：常作“Kanban管理”（来自日语“看板／カンバン Kanban”），亦称“看板方式”、“视板管理”，是丰田生产模式中的重要概念，指为了达到及时生产（JIT）方式控制现场生产流程的工具。及时生产方式中的拉式生产系统可以使信息的流程缩短，并配合定量、固定装货容器等方式，而使生产过程中的物料流动顺畅。

### (b)看板在项目中的载体

- 实体白板/黑板：实体工具。这是敏捷开发团队中用的最多，最直接的一种看板类型，且适合团队所有成员都在一个办公室工作的环境。
  - 优点：一目了然，可以传递可视化信息并加强进度控制，方便工作成员展示自己的任务和进度，起到合理分配资源的作用，还可以提高成员间互相竞争的意识。
  - 缺点：没有历史记录，虽然可以使用不定期的拍照来解决，但是还是不方便追溯。
  - 包含的元素：白板/列表/便签纸/图钉和磁铁

- 互联网式看板：软件化的工具。
  - Trello：https://trello.com/
  - WeKan：https://wekan.io/ 
  - leangoo：https://www.leangoo.com/  

### (c)项目管理在看板中的职责分类

![项目管理主导型](https://github.com/SuBruce/IT-Project-Management/blob/master/Homework06/images/08.png)

- 项目管理主导型：在这种模式中，项目管理是整个团队的大总管，可以清楚地了解到各个成员的优缺点，分配合适的任务给成员。
  - 优点：注重每个成员的原始任务分工，在明确了分工的前提下来管理每个成员的任务进度。
  - 缺点：必须要求原始分工合理，然后才能进行任务分配监督。
  - 上图最能体现出大总管的主导作用：项目管理把任务分配给Jone、Alex、Tom或者Marco，成员只要完成自己的任务就好。  

<br/>

![成员主导型](https://github.com/SuBruce/IT-Project-Management/blob/master/Homework06/images/09.png)  

- 成员主导型：即项目管理要把项目拆分成各个小任务，然后成员自己去“抢”任务。
  - 优点：鼓励成员主动承接任务，多劳多得，有利于激发成员的积极性。
  - 缺点：任务分配可能有争议，且成员能力和任务可能不匹配。
  - 上图是成员主导型的看板展示。  
  
### (d)根据团队的规模增减看板

- 如果你是一个后端的开发主管，那你的手下肯定都是后端，则列表项就是最基本的Todo、Doing、Done三列。
- 如果你是一个技术部的老大，你管理者程序员、测试、运维，那你的列表项可以是Todo、Dev-Doing、Dev-Done、Testing、Deploy五列。
- 如果你是一个产品制作人/产品经理，你的团队成员包含了一个产品创建所需要的所有人员，那你可能需要2个看板，一个是需求池看板，一个是迭代流程的看板。

### (e)总结

- 看版的作用主要是一种时间绩效激励型的管理工具，在管理层能够清楚了解到项目整体进度的同时，能够清楚地了解到成员的工作进度和状态。
- 管理时，看板列表的列属性能够灵活替换增加，但基本上都是按照项目开发周期来设计的。
- 看板应用成功的几个关键要素：
  - 管理层的支持：高层管理者不要对项目作过多的干涉，支持项目组织尝试新的流程。
  - 创新和合作的氛围：创新的氛围包括形成一个创新的奖酬和提升机制以鼓励创新，大胆启用新的方法等方面；优秀的合作则往往决定了项目工作成功与否。
  - 授权给团队：看板管理需要团队有相应的决策权，同时也要求团队成员具备较强的自主意识和发现问题、分析问题、解决问题的能力。
  - 突破限制：遵循看板的流程思路，不要被过去的流程所限制。

