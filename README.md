# AI4S
AI for Science 
- 1、缘起
  - 科学研究：数据驱动的开普勒范式or原理驱动的牛顿范式
  - 牛顿范式：函数逼近，有维数灾难
  - 深度神经网络：对高维函数有效逼近，形成AI For Science基础
    - 图像识别：逼近高维函数（图片到内容的映射）
    - 人脸图片生成：逼近高维概率分布（人脸照片看成图像空间的随机变量）
    - AlphaGo：解高维Bellman方程（最优策略满足方程）

- 2、AI for Science 三大途径
  - 处理数据的新方法（AI）
    - 2020年 DeepMind：AlphaFold 2 （蛋白折叠是典型高维问题）
  - 处理物理模型（基本原理）的新方法
    - 传统分子动力学：猜、经验力场——不可靠；第一性原理方法——可靠，但效率差
    - 机器学习方法——量子力学模型提供数据，机器学习方法提供模型——既可靠，又有效
    - DeePMD（深度势能分子动力学）：基于机器学习的Deep Potential方法，依靠量子力学模型提供训练数据，用深度神经网络对高维势函数进行拟合，就可以同时保证算法的准确性和高效性。
    - 2018年 DeepModeling开源社区
    - 2020年 ACM Gordon-Bell Prize
    
<div align=center>
<img src="https://user-images.githubusercontent.com/118708553/210033847-bdfa4100-c35b-44b7-9b4a-cb277f3bb771.png"/>
</div>


  - 模型驱动与数据驱动方法的深度融合
    - 场景：药物设计、天气预报、受控热核反应等

<div align=center>
<img src="https://user-images.githubusercontent.com/118708553/210033969-ade5693b-ec52-454e-932b-9e3ed0bb3c82.png"/>
</div>

    - 涉及挑战：数据同步、观测与模型的同步学习、强化学习、相关实验设计等
    - 系统化工程：挑战更大，也意味着巨大空间与机会

- 3、基于AI for Science的工业新业态
  - 宏观层面的工业制造：新的CAx体系——CAA、CAD、CAM等
    - CAD/CAE 一体化、智能化：把工程设计关心的指标（最大应力、阻力、电容等）直接表示成为几何形状的函数，使得基于工程目标的设计（不仅仅是几何设计）成为可能
    - 比如中科大杨周旺老师：九韶一体化内核。比如湘潭大学的魏华祎老师。
  - 微观层面的工业制造：新产业

<div align=center>
<img src="https://user-images.githubusercontent.com/118708553/210034018-9688b93e-6413-46f6-abaf-7e8606ddbf2f.png"/>
</div>

- 4、AI for Science 基础设施
  - 数据
    - 高质量数据库的建设
      - 新的实验手段（比如自动化实验平台）
      - 数据合作平台
    - 知识库的建设
      - 从文献到知识库
      - 新的知识工程
  - 模型：不同时空尺度下各种物理模型，包括终极难题多体薛定谔方程和Navier-Stokes方程

<div align=center>
<img src="https://user-images.githubusercontent.com/118708553/210034981-c6e85f24-fe3f-4878-a827-dd1d67736276.png"/>
</div>


<div align=center>
<img src="https://user-images.githubusercontent.com/118708553/210034076-645abd5c-451a-45ee-b8e8-dffc9ec021b3.png"/>
</div>
  - 算法
    - 数据同化算法
    - 高维空间的exploration/sampling算法
    - 处理稀有事件的算法（时间尺度）
    - 其他时间尺度问题的算法（如奇异扩散算法）
  - 算力
    - 优化算力资源（如深势科技云原生科学计算平台Lebesgue）
    - 专用芯片（例如湖南大学 NVNMD）

- 5、投资视角

<div align=center>
<img src="https://user-images.githubusercontent.com/118708553/210034134-099d5cd8-1b55-473b-ba78-ae3cfa22d59c.png"/>
</div>

  - 医疗
    - AI靶点发掘
    - AI+小分子药
    - 肠脑轴
  - 合成生物学
    - AI非天然产物设计：
      - 蛋白折叠，蛋白设计：做药
        - 膜蛋白/信号蛋白
      - 酶设计：酶制剂（催化反应）
    - AI天然产物挖掘
      - 抗生素挖掘
      - 保健品：类似辅酶Q10
      - 医疗美容护肤品：类似S22 MIBOM贻贝粘蛋白、玻尿酸等
      - 老药新用
    - 符合双碳的合成生物学 生产过程中固定二氧化碳（无机碳到有机碳）
      - 藻类值得看
    - 精准医疗
  - 基因编辑
    - 原创性的基因编辑工具（如CRISPR）
  - DNA引擎：纳米机器人模拟 药物递送
  - 化学
    - AI+化合物合成路径选择、生成、优化
  - 材料学
    - 机器学习+塑料
  - 物理学
    - 仿真
    - AI+有限元
  - 气象

- 6、案例：
  - AI4S 标志型公司：
    - DeepMind
    - 深势科技 
  - AI 材料
    - AI材料的逻辑：想要某些材料特性（比如说，轻便又坚韧），通过寻找可以产生这些特性的物理和化学结构，以及需要通过哪种处理过程，比如对金属进行熔化或捶打，来创造这样的结构。建立“材料云”数据库，虽不完美但已为科学家们创造了捷径
    - 材料项目链接：https://materialsproject.org/about 。材料云链接：https://www.materialscloud.org/
    - 西北大学的Wolverton团队、斯坦福大学SLAC国家加速器实验室的Apurva Mehta、麻省理工学院材料科学家Elsa Olivetti用AI来解决如何生成新的金属玻璃混合物的问题。这比起在实验室进行实验快了200倍。（数据+模型）
    - 瑞士洛桑联邦理工大学研究员Nicola Marzari利用数据库查找可剥离的3D材料，以创建仅有一层的2D材料
  - AI 制药
    - AI制药 
    - 2018年2月，AI新药研发公司Insitro成立，2021年完成C轮融资后累积资金额达7.43亿美元。Insitro致力于利用大数据、机器学习以及生命科学领域的融合创新技术，重新构建药物设计过程.

