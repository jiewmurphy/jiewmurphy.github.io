<center>
     <h1>王杰</h1>
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             18610652570
         </span>
         ·
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             jiewmurphy@163.com
         </span>
         ·
         <span>
             <img src="assets/rss-solid.svg" width="18px">
             <a href="https://scholar.google.com/citations?user=YTeQmzEAAAAJ&hl=en">学术论文</a>
         </span>
     </div>
</center>

## <img src="assets/info-circle-solid.svg" width="30px"> 个人信息 

 - 女，1988 年出生
 - 求职意向：程序分析专家
 - 意向工作地：北京
 - 工作经验：10 年
 - 现工作单位：华为／北京环保园

## <img src="assets/graduation-cap-solid.svg" width="30px"> 教育经历

- 博士后，北大/阿里联合培养，导师熊英飞/郭振宇，计算机与理论，2018.12~2020.12
- 博士/硕士，中国科学院大学/软件所，计算机软件与理论，2012.9~2018.6
- 学士，吉林大学，计算机科学与技术专业，GPA(前3%/370人)，2008.9~2012.6
- 英语：CET4/6

## <img src="assets/briefcase-solid.svg" width="30px"> 工作经历

- **2022.5~今，华为，ICT产品与解决方案部-伽罗瓦实验室，程序分析技术专家/19级，团队技术负责人/10+人**
 
- **2018.7~2022.5，蚂蚁集团，数据技术-分布式计算部门，技术专家/P7，部门程序分析能力负责人/6人**

## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历

*在职期间项目细节不在简历中透露*

- **2024 - 大模型辅助研发效率提升**
  
  *大模型，RAG, SFT, Prompting*

  据copilot统计，大模型辅助研发生产力提升了近两倍。本项目利用大模型辅助部门内AI辅助设计、开发、测试、运维等方面的十几个场景并进行关键技术突破。

- **2024 - 相似代码检索**

   *代码克隆，LLM, embedding, GNN, 子图匹配，代码属性图*

  相似代码检索可应用在代码搜索、代码克隆等广泛的应用场景，当前大模型在信息检索方面取得重大进展，然而代码与自然语言存在巨大差别。代码重命名、语句顺序、计算的括号展开结合律等变化都可能导致代码不同但语义相同，当前的embdding大模型, code embedding算法等在语义相似方面存在巨大差距。
  

- **2023 - 代码缺陷检查**

  *内存缺陷，代码安全，C语言，静态检查，CSA，符号执行*

  代码安全问题是系统研发中的top问题，像资源泄露、重复释放、释放后使用、空指针、缓冲区溢出等问题通常在运行时触发并引发系统宕机等严重故障。此类问题对静态分析的精度具有很高的要求（上下文、路径、流、域敏感），否则因为太高的误报而导致功能无法使用。本项目在公司多个产品线得到大规模推广，收获一致好评，并带领团队获得多个重大奖项。

- **2022 - 大规模静态分析**

  *指针分析，C语言，andersen算法*

   并行框架：指针分析等程序分析算法是指数级复杂度，对内存和算力要求都很高，本项目探索了采用图计算技术研发程序分析的并行框架，该框架将程序分析图算法切分成多个子图和子图间通讯的分布式图计算问题来解决计算上的扩展性，并采用核外计算/分布式图数据库实现在存储上的扩展性。项目基于andersen算法完成了预研，后因工作调动不再继续。
  call graph分析：准确分析call graph可帮助业务分析组件耦合、依赖关系、循环调用等软件架构问题，以及是进行程序分析等任务的基础能力。然而在系统代码规模在千万行到上亿行时，此任务变得困难。本项目突破该问题并被公司成熟的架构看护工具所使用。
  

- **2020 - 静态污点分析：面向大规模java应用的污点分析工具**

  *数据流分析，java/soot，IFDS，按需分析，稀疏值流关系*
  
  蚂蚁业务涉及几千个应用/微服务，很多应用间密切联系，调用链路长，数据来源广，系统复杂度高。
  一旦一个系统或者其依赖的系统出现问题或发生变更，可能导致信息流异常，严重情况下会引发资金流异常、产生资损、隐私数据泄露等问题。
  针对这些问题，<b>追踪关键数据字段如何在单个系统内及系统间传播</b>成为一项重要任务。 然而 ，一个系统可能包含上万条数据链路，
  与几十个系统直接或间接关联，依靠人工发现数据链路成本高且不准确。 本项目提供一个（在线）污点分析/数据血缘平台，
  自动追踪字段级别数据流转链路， 目前已经或正在应用于变更防御、资金分母、 充分灰度、 全栈数据链路构建等场景。
  本人独立负责工具底座-污点分析技术的研发， 相关工作发表CCFA类论文1篇（FSE20，一作），专利2篇。【PPT: FSE20, 从Flowdroid到Aflow】

- **2022 - Python即时编译优化**

  *Python, 即时编译/jit，向量化/并行化，numba, dataframe*
  
  Python 是人工智能和机器学习开发的主流编程语言之一，但在处理大规模数据时仍面临巨大的性能挑战。
  一方面python是解释型语言，比C++慢20多倍；另一方面，GIL限制了程序并发，无法利用多核优势。
  我们的目标是提供一种简单有效的python即时编译工具，用户仅需添加一个@jit注解即可完成一段代码的优化。
  工具通过编译技术将python代码编译成高性能的机器码，同时把可并发逻辑（如for循环）自动优化成多线程代码，从而获得性能收益。
  利用编译技术还可以方便的应用很多传统优化策略：如loop fusion，死代码消除，公共表达式消除等。
  本人为该项目负责人，目前应用在了两个业务场景中，初期效果达到约5倍性能提升。【PPT：工作简介】

- **2019 - 分布式GC+性能优化：动态数据流（分布式）系统GC及性能优化工具**

  *分布式计算引擎，ray，gc，调度性能*
  
  近年来，动态数据流系统因为其强大的表达力及编程易用性得到广泛关注。 然而其与静态数据流系统（如tensorflow, flink)
   在性能方面存在差距。 根本原因在于动态数据流系统的调度图是动态增长的， 运行时对对象的生命周期和
  任务的全局依赖关系未知，无法像静态数据流那样提前进行调度规划。本项目针对ray的对象管理和性能进行了优化，
  一方面通过静态分析获取任务依赖的情况， 并通过插桩自动优化具有特性模式的代码；另一方面因为静态分析不能覆盖所有情况，
  我们提出一个分布式gc的动态方案， 具有轻量、 容错特性。 本人为该项目负责人。【PPT：工作简介】

- **2021 - 根因分析/故障诊断：基于日志的根因定位工具**
  
  *根因分析，日志分析，DSL*

  日志被广泛应用于错误排查。 然而基于日志排查分布式系统中的错误并不简单。排查过程可能涉及分析复杂的协议(如故
  障恢复，分布式GC)、 随机环境事件（节点宕机），计算语义错误 ，及特定的事件时序等因素，需要开发者对系统高度熟悉、
  且投入大量时间。 随着业务规模的增大，错误诊断的成本和开销尤为凸显，保姆式的运维不再适用。 如何高效地进行错误检测、
  定位、 以及诊断是当前Ray团队的一个重要任务。 本项目研发了一种基于规则的故障定位方法 ，定义了一套DSL来描述故障特征，
  工具在设计上具有表达能力强、高易用、高可扩展和高性能的特点。 正在探索自动化异常检测、 智能运维等场景的方案。
  此项目依托于校企合作，本人为项目负责人，已发表1篇专利。【PPT：工作简介】

- **2017 - 并发错误检测**

  *javascript，并发错误检测，原子性违反，事件驱动*

  当前javascript作为全栈语言被广泛使用，本项目针对javascript中的并发错误进行研究。js是事件驱动的，当代码缺少同步或环境
  的不确定等因素时导致执行顺序不确定，进而引发并发错误。因此我们首先对js中的并发错误进行了实证研究。
  根据统计，原子性违反错误占65%，我们提出一种原子性违反检测工具，我们首次为Node.js应用程序设计了
  happen-before关系并为数据访问（包括内存数据访问和异步数据访问） 建立了几种原子性违反模式。与相关方法Node.fz相比，我们的工具在效率上和发现错误的能力上具有明显优势。
  本人独立负责此项目，发表CCFA类论文2篇(ASE17, ICSE19)。

- **2015 - 故障重现/记录重放**

  *故障重现，记录重放，程序切片，动态分析*
  
  WEB应用成为发展最为迅速的软件系统， 同时WEB应用的可靠性也变得越来越重要。记录重放技术通常被用来有效的重现WEB应用中的错误。
  然而当程序长时间的运行时，记录重放工具会生成大量的事件日志，例如，MugShot 每分钟将产生75-795K的事件日志。
  利用原始事件日志进行调试， 开发者需要审查大量无关的事件及代码 ，很难定位与调 试错误。 JSTrace的目标是移除事件日志中与错误无关的事件，
   从而快速重放错误，便于调试。 JSTrace基于动态程序切片的实现，它根据运行时收集到的数据依赖信息来构建事件间的依赖关系，
  从而找出与错误相关的事件。 根据我们的实验结 果，JSTrace可以有效的移除与错误不相关的事件。
  本人独立负责此项目，发表CCFB类论文2篇 (ISSRE15, JSS18, FSE16-SRC，ICST18)。

## 论文列表

- <b>Jie Wang</b>, et.al,. <i>Combating the Problem of Indirection in Distributed Dynamic Dataflow</i> (ant group, technique report).
- <b>Jie Wang</b>, Yunguang Wu, Gang Zhou, Yiming Yu, Zhenyu Guo, Yingfei Xiong. <i>Scaling static taint analysis to
industrial SOA applications: a case study at Alibaba</i> (FSE2020, CCFA, EI).
- Xiaoning Chang, Wensheng Dou, Yu Gao, <b>Jie Wang</b>, Jun Wei, Tao Huang. <i>Detecting atomicity violations for eventdriven
Node.js applications</i> (ICSE2019, CCFA, EI)
- <b>Jie Wang</b>, Wensheng Dou, Yu Gao, Chushu Gao, Feng Qin, Jun Wei. <i>A Comprehensive Study on Real World
Concurrency Bugs in Node.js</i>. In proceedings of the 32nd IEEE/ACM International Conference on Automated
Software Engineering (ASE 2017, CCF A, EI).
- <b>Jie Wang</b>, <i>Characterizing and Taming Non-deterministic Bugs in JavaScript Applications</i>. In proceedings of the
32nd IEEE/ACM International Conference on Automated Software Engineering (ASE 2017-doctoral symposium, CCF A, EI).
- <b>Jie Wang</b>. <i>Constraint-based Event Trace Reduction</i>. In proceedings of the 24th ACM SIGSOFT International
Symposium on the Foundations of Software Engineering (FSE 2016-SRC, CCF A, EI).
- <b>Jie Wang</b>, Wensheng Dou, Chushu Gao, Jun Wei. <i>JSTrace: Fast Reproducing Web Application Errors</i>. In Journal
of Systems and Software (JSS, CCF B, EI).
- <b>Jie Wang</b>, Wensheng Dou, Chushu Gao, Jun Wei. <i>Fast Reproducing Web Application Errors</i>. In proceedings of the
26th IEEE International Symposium on Software Reliability Engineering (ISSRE 2015, CCF B, EI).
- <b>Jie Wang</b>, Wensheng Dou, Chushu Gao, Jun Wei. <i>Context-Based Event Trace Reduction in Client-Side JavaScript
Applications</i>. In proceedings of the11th IEEE Conference on Software Testing, Validation and Verification (ICST 2018, CCF C, EI).

## 获得荣誉

- 2024，内源金徽章项目
- 2024，分委会优秀项目
- 2023，优秀教练*2
- 2023，总裁奖
- 2022，优秀教练
- 2022，金网络
- 2020，蚂蚁，年度金钥匙（创新奖）
- 2017，中国科学院博士生国家奖学金
- 2016，中国科学院大学三好学生标兵
- 2013、 2014、 2015、 2016，中国科学院大学三好学生
- 2013、 2014，中国科学院大学优秀学生班干部
- 2012，中国科学院软件所优秀实习生奖学金
- 2009、 2010、 2011、 2012，吉林大学国家励志奖学金
