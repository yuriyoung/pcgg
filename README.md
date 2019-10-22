## Procedural Content Generation For Games 游戏过程(程序)化内容生成

- A.1 伪随机数生成器 (Pseudo-Random Number Generators)
  - 柏林噪声(Perlin Noise): 一种基于PRNG的噪声生成器，生成数据点的映射（随机值），如地图数据点是由种子PRNG通过插值法生成。 
- A.2 生成语法(GG, Generation Grammar)
  
  *对单个单词按规则进行操作，生成语法正确的句子。*
  
  - A.2.1 L系统 (Lindenmayer System): 由符号组成的语法构建出物体的特征，L系统生成字符串描述结构或对象的行为，广泛应用于植被生成。
  - A.2.2 拆分语法 (Split Grammars)

- A.3 图像过滤（Image Filtering）

   *图像过滤的主要目标是在（主观）测量或改善图像质量方面提高图像质量。调整图像的某些特征以显示（部分）隐藏的信息。*
   
  - A.3.1 二值图像形态学 (Binary Morphology)
  - A.3.2 卷积滤波器 (Convolution Filters)
  
- A.4 空间算法（Spatial Algorithms）
  - A.4.1 平铺和分层 (Tiling and Layering): 平铺是一种通过分解游戏来创建游戏空间的技术，映射成网格。网格不仅限于矩形大小，六边形也很常见。格网是2D数据结构，但是等轴测投影可以耦合到网格以创建3D视觉地图。分层是一种集成了多个网格（称为图层）的技术。
  - A.4.2 网格剖分 (Grid Subdivision): 一种用于对象生成的迭代和动态技术。网格细分算法用于例如Patch-LOD算法，用于迭代地向对象添加细节。使用示例：过程生成地形的渲染。
  - A.4.3 分形 (Fractals):  由自身副本组成的递归图，如雪花。
  - A.4.4 泰森多边形/图 (Voronoi Diagrams): 将度量空间分解为多个部分其大小和形状由度量中种子点的位置确定空间。
  
- A.5  复杂系统的建模和仿真 (CS, Modeling and Simulation of Complex Systems)
  - A.5.1 元胞自动机 (Cellular Automata)
  - A.5.2 张量场 (Tensor Fields)
  - A.5.3 智能代理仿真 (Agent-based Simulation)
  - A.5.4 其他复杂系统和理论 (Other Complex Systems and Theories)
  
- A.6  人工智能 (Artiﬁcial Intelligence)
  - A.6.1 遗传算法 (Genetic Algorithms)
  - A.6.2 人工神经网络 (Artiﬁcial Neural Networks)
