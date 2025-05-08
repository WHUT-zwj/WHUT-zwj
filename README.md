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


⚡ (III) Project 3: ```AI-Generated Face Image Recognition Based on Dual-Path Feature Extraction``` (Core Team Member) (September 2024 - December 2024).<br>
**Task:** To accurately identify and distinguish subtle feature differences between AI-generated and real face images under complex data distributions.<br>
**Solution:** Proposed an AI-generated face image recognition method based on DualFace-RCSD (Dual-ResNet Face Real-Synthetic Cascaded Detector). This approach utilizes parallel ResNet50 networks as the backbone to process images separately after MTCNN face detection and the original images. It then fuses the confidence scores and multi-dimensional features from the predictions of both ResNet50 networks, ultimately employing a decision tree for precise identification of AI-generated faces.<br>
**Achievement:** National Second Prize in the Global Campus AI Algorithm Elite Challenge.<br>

⚡ (IV) Project 4: ```Joint Decision-Making for Crop Planting and Sales Based on a Multi-Objective Stochastic Programming Model``` (Project Lead) (September 2024).<br>
**Task:** To address the crop planting optimization problem in rural North China, with key challenges including the uncertainty of price fluctuations, complex inter-crop relationships, and balancing long-term risk management.<br>
**Solution:** Developed a multi-objective stochastic programming model, integrating Monte Carlo simulation with the NSGA-II algorithm to determine optimal planting strategies that balance profitability and risk.<br>
**Personal Contributions:** Responsible for modeling and framework construction, writing sections on model and result analysis, visualization, and programming the penalty function patching.<br>
**Achievement:** Hubei Provincial First Prize in the National College Student Mathematical Contest in Modeling.<br>

⚡ (V) Project 5: ```Apple Recognition and Picking Point Localization Based on Residual Neural Network``` (Project Lead) (April 2024).<br>
**Task:** To address the challenges of apple recognition and localization for picking robots under conditions of occlusion, overlap, and light/shadow interference.<br>
**Solution:** Initially, apples were segmented using fuzzy clustering. Subsequently, an improved Canny edge detection algorithm was utilized for localization. Finally, the images were transformed into the HSV color space for classification using ResNet50.<br>
**Personal Contributions:** Responsible for modeling and framework construction, writing sections on model and result analysis, visualization, and programming the fuzzy clustering and ResNet50 implementation.<br>
**Achievement:** International First Prize (Outstanding Winner equivalent) in the Asia-Pacific Mathematical Contest in Modeling.<br>

⚡ (VI) Project 6: ```Poverty Data Mining and Relative Poverty Identification under Big Data``` (Core Team Member).<br>
**Task:** To address the multi-dimensional complexity of relative poverty identification and establish a scientific identification system for precise classification.<br>
**Solution:** Constructed a multi-dimensional poverty-revitalization synergistic indicator system, performed feature selection based on Random Forest, and utilized a Bayesian cost-sensitive neural network for identification.<br>
**Personal Contributions:** Responsible for modeling and framework construction, writing sections on preprocessing, model, and result analysis, visualization, and programming the feature selection implementation.<br>
**Achievement:** First Prize in the Central South Regional Competition of the China Collegiate Computer Design Contest.<br>

### III. Future Plans
🌱 I plan to delve deeply into the frontiers of Artificial Intelligence during my doctoral studies. Given the current trend of high interdisciplinary integration among AI branches, I aim to maintain an open mind to actively learn and explore various directions, including but not limited to Machine Learning Theory, Computer Vision, Natural Language Processing, Large Model Alignment or Lightweighting, Embodied Intelligence, and Large Model Safety. I aim to identify a specific research topic that ignites my passion.<br>
🌱 My current research interests are particularly focused on directions built upon a solid foundation of theoretical derivation, can be closely integrated with deep learning models, and ultimately have clear vertical application scenarios. I aspire to explore the fundamental principles of intelligent behavior through rigorous mathematical modeling and theoretical analysis. Furthermore, I am committed to applying these theoretical insights to enhance existing deep learning algorithms' performance, interpretability, or generalization capabilities. For instance, my current exploration involves leveraging manifold geometry to approximate optimal transport for multi-modal time series alignment. Through this, I hope to uncover the intrinsic nature of how neural networks learn distributions and topological structures, and even investigate whether this approach can address the "shallow alignment" problem in large model safety, as well as how to discover multiple research problems and develop various models stemming from optimal transport theory.

### IV. Contact Information
Phone: 13534926288
Email: whutzwj@163.com

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
