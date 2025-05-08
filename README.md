## Welcome to Weijie Zhu's Homepage 😄😄
✨ I am an undergraduate student majoring in Information and Computational Science (Class of 2022) at Wuhan University of Technology. **I am on the postgraduate recommendation track this year** and possess a **strong aspiration to pursue doctoral studies!** <br>
✨ Research Skills: (1) **Strong practical skills and self-motivation.** I have extensive experience in reproducing deep learning projects and practical experience in data mining. I have independently studied the deployment and fine-tuning of large models and the construction of the MCP Server. Furthermore, I possess considerable experience in mathematical modeling (primarily as a modeler, with auxiliary programming and writing responsibilities). (2) **Solid research experience.** I have undergone one and a half years of comprehensive research training, enabling me to independently complete the entire research workflow, including deep learning framework construction, experimental design and implementation, visualization, academic paper writing, and submission. (3) **Theoretical derivation capabilities.** My current research focuses on deriving an approach that utilizes manifold geometry to approximate optimal transport for multimodal time series alignment, producing concise yet impactful work. (4) **English proficiency:** I have successfully passed CET-4 and CET-6, can write academic papers in English, and maintain a daily habit of reading English literature. The following section details my specific experiences: <br>


### 一、科研论文
💬（一） 期刊论文：SCI一区Expert Systems with Applications独立一作Under Review<br> 《GHOST: Sentiment-gated Mamba and Stock-wise Tokenization for Enhanced Stock Prediction》<br>
**痛点：** <br>
（I） 当前的情绪分析方法对市场情绪量化不足，缺乏针对市场波动的动态自适应整合机制。<br>
（ii） Transformer的Quadratic Complexity，限制了对股票的长期预测，同时缺乏金融特有的时间归纳偏差。<br>
（iii） 传统的temporal tokenization 范式强行将多股票特征合并，削弱了股票相关性建模，同时大幅增加了计算成本。<br>
**创新点：** <br>
（i） 从数量、极性、分布三个方面提取新闻文本中的市场情感，并通过层次化情感门控与股票数据进行动态自适应融合；<br>
（ii） 利用股票共享的动态参数Mamba进行高效的股票序列建模，同时提供特定的金融时序偏置来精准捕捉时序依赖性；<br>
（iii） 提出Stock-wise Tokenization并计算股票token间的注意力，从而确保时间线性计算复杂度的同时，挖掘股票的相关性。<br>
**延续工作：** 尝试推导利用流形几何近似最优传输来对齐情感数据和股票数据，进而推广到多模态时序对齐。<br>
**个人贡献：** 模型搭建、实验设计与实现、可视化和论文写作<br>
```项目链接为：```https://github.com/WHUT-zwj/GHOST <br>

💬（二） 会议论文：CCF B European Conference on Artificial Intelligence(ECAI) 二作Under Review<br>
《LAMM-ViT: AI Face Detection via Layer-Aware Modulation of Region-Guided Attention》<br>
**痛点：** 
(i) 现有检测方法对新型生成技术的泛化能力不足，常过度依赖表面伪影而非深层结构性缺陷。<br>
(ii) 传统注意力机制缺乏跨层动态调整能力，难以有效捕获伪造人脸的层次化、区域性不一致特征。<br>
(iii) 高级生成模型在维持面部各区域间细微结构关联性方面存在固有局限，此弱点未被充分利用。<br>
**创新点：** 
(i) 提出区域引导多头注意力 (RG-MHA)，利用面部关键点精确引导模型聚焦于区域间的结构不一致性。<br>
(ii) 引入层感知掩码调制 (LAMM)，实现跨网络深度的区域注意力动态调整，以捕获多层次伪造特征。<br>
(iii) 设计掩码多样性损失 (Ldiv)，激励模型学习多样化的检测策略，增强对未知生成技术的泛化性能。<br>
**个人贡献：** methodology写作，可视化，协助对比实验


### II. Research Project Experience<br>
`Relevant project files:` https://github.com/WHUT-zwj/Project-Introduction <br>
⚡ (I) Project 1: Led a Provincial-level Undergraduate Entrepreneurial Practice Project — ```Wuxian Technology — Leader in Automotive 4D Imaging Millimeter-Wave Radar Antennas``` (March 2024 - Present).<br>
**Responsibilities:** As the primary project lead, I managed the team and coordinated the project's application, execution, and conclusion. I was also primarily responsible for developing the team's MIMO-based FMCW radar algorithms.<br>
**Achievements:** As the second person-in-charge, the project secured Silver Awards in both the Hubei Provincial China International College Students' 'Internet+' Innovation and Entrepreneurship Competition and the Hubei Provincial iCAN Innovation and Entrepreneurship Competition. Additionally, I engaged in technical exchanges with companies such as Desay SV (Nanjing).<br>

⚡ (II) Project 2: ```Olympic Medal Prediction Based on Spatio-temporal Distribution and Zero-Truncation Characteristics``` (Project Lead) (January 2024).<br>
**Task:** To address the highly skewed distribution and zero-truncation issues in Olympic medal counts, while incorporating the coach effect, identifying both previously medaled and first-time medaling countries, and quantifying uncertainty.<br>
**Solution:** We mined the spatio-temporal characteristics of medal trends, introduced the Tobit model to overcome zero-truncation limitations, quantified the coach effect using AHP-GRA, and employed Random Forest for medal prediction.<br>
**Personal Contributions:** Responsible for modeling and framework construction, writing sections on model and result analysis, visualization, spatio-temporal feature mining, and Tobit model programming and implementation.<br>
**Achievement:** Meritorious Winner (International First Prize equivalent) in the MCM/ICM International Collegiate Mathematical Contest in Modeling.<br>


⚡（III） 项目三：```基于双路径特征提取的 AI 生成人脸图像识别``` 2024-9到2024-12<br>
**任务：** 如何在复杂的数据分布下精确识别和区分AI生成与真实人脸图像的细微特征差异。<br>
**方案：** 提出了基于DualFace-RCSD (Dual-ResNet Face Real-Synthetic Cascaded Detector)的AI生成人脸图像识别。采用并行的ResNet50网络作为backbone，分别处理MTCNN人脸检测后的图像和原始图像，并融合两个 ResNet50 网络预测结果的置信度以及多维特征，最终使用决策树实现对 AI 生成人脸的精确识别。<br>
**成果：** 全球校园人工智能校园算法精英挑战赛全国二等奖<br>

⚡(IV) 项目四：```基于多目标随机规划模型的农作物种植与销售联合决策```（负责人）2024.9<br>
**任务：** 解决华北乡村农作物优化种植问题，难点在于价格波动不确定性、作物间复杂关系及长期风险管理的平衡。<br>
**方案：** 建立多目标随机规划模型，结合蒙特卡洛模拟与NSGA-II算法求解最优种植策略，平衡效益与风险。<br>
**个人贡献：** 建模与框架搭建，模型与结果分析部分写作、可视化、罚函数打补丁部分编程实现。<br>
**成果：** 全国大学生数学建模竞赛湖北省一等奖

⚡（V） 项目五：```基于残差神经网络的苹果识别及采摘点定位```（负责人）2024.4<br>
**任务：**解决采摘机器人在遮挡、重叠和光影干扰下的苹果识别与定位难题。<br>
**方案：**首先基于模糊聚类进行苹果分割，再利用改进的Canny边缘检测定位，后转化到HIV空间进行Resnet50分类。<br> 
**个人贡献：**建模与框架搭建，模型与结果分析部分写作、可视化、模糊聚类和Resnet50编程实现。<br>
**成果：**亚太地区大学生数学建模竞赛国际一等奖<br>

⚡（VI） 项目六：```大数据下的贫困数据挖掘与相对贫困识别```（第一成员）<br>
**任务：** 解决相对贫困识别的多维复杂性问题，建立科学的识别体系实现精准分类。<br>
**方案：** 构建了多维贫困-振兴协同指标体系，基于随机森林进行特征选择，利用Bayes成本敏感神经网络进行识别。<br>
**个人贡献：** 建模与框架搭建，预处理、模型、结果分析部分写作、可视化、特征选择编程实现。<br>
**成果：** 计算机设计大赛中南赛区一等奖<br>

### 三、未来规划

🌱我计划在博士阶段深入探索人工智能的前沿领域。鉴于当前人工智能各分支高度交叉融合的趋势，我希望能够以开放的心态积极学习和探索包括但不限于机器学习理论、计算机视觉、自然语言处理、大模型对齐或轻量化、具身智能、大模型安全等多个方向，致力于寻找能够激发我研究热情的具体课题。<br>
🌱我目前的研究兴趣尤其聚焦于那些以坚实理论推导为基石，并能与深度学习模型紧密结合，最终能有垂直应用场景的研究方向。我期望通过严谨的数学建模与理论分析，探索智能行为的本质规律，并致力于将这些理论洞见应用于改进现有深度学习算法的性能、可解释性或泛化能力，包括我现在正在尝试的利用流形几何近似最优传输来进行多模态时间序列对齐，正是希望能够挖掘神经网络学习其分布和拓扑结构的内在本质，甚至乎是否能够应对大模型安全对齐中的“浅层对齐”问题，以及如何才能从最优传输这一理论去发现多个问题，延伸出多个模型。

### 四、联系方式
电话：13534926288
电子邮箱：whutzwj@163.com

<!--
**WHUT-zwj/WHUT-zwj** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
