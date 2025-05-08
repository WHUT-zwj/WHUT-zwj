## Welcome to Weijie Zhu's Homepage 😄😄
✨ I am an undergraduate student majoring in Information and Computational Science (Class of 2022) at Wuhan University of Technology. **I am on the postgraduate recommendation track this year** and possess a **strong aspiration to pursue doctoral studies!** <br>
✨ Research Skills: (1) **Strong practical skills and self-motivation.** I have extensive experience in reproducing deep learning projects and practical experience in data mining. I have independently studied the deployment and fine-tuning of large models and the construction of the MCP Server. Furthermore, I possess considerable experience in mathematical modeling (primarily as a modeler, with auxiliary programming and writing responsibilities). (2) **Solid research experience.** I have undergone one and a half years of comprehensive research training, enabling me to independently complete the entire research workflow, including deep learning framework construction, experimental design and implementation, visualization, academic paper writing, and submission. (3) **Theoretical derivation capabilities.** My current research focuses on deriving an approach that utilizes manifold geometry to approximate optimal transport for multimodal time series alignment, producing concise yet impactful work. (4) **English proficiency:** I have successfully passed CET-4 and CET-6, can write academic papers in English, and maintain a daily habit of reading English literature. The following section details my specific experiences: <br>


### I. Research Papers
**💬 ( I ) Journal Paper:** SCI Q1, Expert Systems with Applications, Independent First Author, Under Review<br>

**GHOST: Sentiment-gated Mamba and Stock-wise Tokenization for Enhanced Stock Prediction** <br>
**Pain Points:** <br>
**( i )** Current sentiment analysis methods exhibit insufficient market sentiment quantification and lack dynamic adaptive integration mechanisms for market fluctuations.<br>
**( ii )** Transformer-based models' quadratic complexity limits long-term stock prediction while lacking finance-specific temporal inductive biases.<br>
**( iii )** Traditional temporal tokenization paradigms forcibly merge multi-stock features, weakening stock correlation modeling while dramatically increasing computational costs.<br>
**Innovations:** <br>
**( i )** Extracting comprehensive market sentiment representations from massive sentiment-analyzed news (polarity, volume, and distribution features), and implementing a Hierarchical Sentiment-gating Layer for dynamic adaptive integration of affective features with trading data.<br>
**( ii )** Dynamically parameterized Intra-Stock Mamba Selection Layer introduces specialized financial inductive biases with time-series linear complexity<br>
**( iii )** Stock-wise Tokenization Layer converts temporal tokens into stock tokens preserving sequence integrity, and Inter-Stock Attention Layer captures market correlations via attention between stock tokens while reducing complexity from temporal sequence ( $O(T^2)$ ) to stock quantity ( $O(N^2)$ ) where $N \ll T$.<br>
**Future Work:** Exploring the derivation of manifold geometry to approximate optimal transport for aligning sentiment data and stock data, to generalize to multi-modal time series alignment.<br>
**Personal Contributions:** Model construction, experimental design and implementation, visualization, and manuscript writing.<br>
```Project Link:``` https://github.com/WHUT-zwj/GHOST <br>

**💬 ( II ) Conference Paper:** CCF B, European Conference on Artificial Intelligence (ECAI), Second Author, Under Review<br>
**LAMM-ViT: AI Face Detection via Layer-Aware Modulation of Region-Guided Attention**<br>
**Pain Points:** <be>
**( i )** Existing detection methods exhibit insufficient generalization capabilities against novel generative techniques, often over-relying on superficial artifacts rather than deep structural flaws.<br>
**( ii )** Traditional attention mechanisms lack cross-layer dynamic adjustment capabilities, making it difficult to effectively capture the hierarchical and regional inconsistencies characteristic of forged faces.<br>
**( iii )** Advanced generative models have inherent limitations in maintaining subtle structural correlations between facial regions, a weakness not yet fully exploited.<br>
**Innovations:** <be>
**( i )** Proposed Region-Guided Multi-Head Attention (RG-MHA), which utilizes facial keypoints to precisely guide the model to focus on structural inconsistencies between regions.<br>
**( ii )** Introduced Layer-Aware Mask Modulation (LAMM), enabling dynamic adjustment of regional attention across network depths to capture multi-level forgery features.<br>
**( iii )** Designed a Mask Diversity Loss (Ldiv) to incentivize the model to learn diverse detection strategies, enhancing generalization performance against unknown generative techniques.<br>
**Personal Contributions:** Methodology writing, visualization, and assisting with comparative experiments.<br>


### II. Research Project Experience<br>
`Relevant project files:` https://github.com/WHUT-zwj/Project-Introduction <br>
⚡ **( I ) Project 1:** Led a Provincial-level Undergraduate Entrepreneurial Practice Project — ```Wuxian Technology — Leader in Automotive 4D Imaging Millimeter-Wave Radar Antennas``` (March 2024 - Present).<br>
**Responsibilities:** As the primary project lead, I managed the team and coordinated the project's application, execution, and conclusion. I was also primarily responsible for developing the team's MIMO-based FMCW radar algorithms.<br>
**Achievements:** As the second person-in-charge, the project secured Silver Awards in both the Hubei Provincial China International College Students' 'Internet+' Innovation and Entrepreneurship Competition and the Hubei Provincial iCAN Innovation and Entrepreneurship Competition. Additionally, I engaged in technical exchanges with companies such as Desay SV (Nanjing).<br>

⚡ **( II ) Project 2:** ```Olympic Medal Prediction Based on Spatio-temporal Distribution and Zero-Truncation Characteristics``` (Project Lead) (January 2024).<br>
**Task:** To address the highly skewed distribution and zero-truncation issues in Olympic medal counts, while incorporating the coach effect, identifying both previously and first-time medaling countries, and quantifying uncertainty.<br>
**Solution:** We mined the spatio-temporal characteristics of medal trends, introduced the Tobit model to overcome zero-truncation limitations, quantified the coach effect using AHP-GRA, and employed Random Forest for medal prediction.<br>
**Personal Contributions:** Responsible for modeling and framework construction, writing sections on model and result analysis, visualization, spatio-temporal feature mining, and Tobit model programming and implementation.<br>
**Achievement:** Meritorious Winner (International First Prize equivalent) in the MCM/ICM International Collegiate Mathematical Contest in Modeling.<br>


⚡ **( III ) Project 3**: ```AI-Generated Face Image Recognition Based on Dual-Path Feature Extraction``` (Core Team Member) (September 2024 - December 2024).<br>
**Task:** To accurately identify and distinguish subtle feature differences between AI-generated and real face images under complex data distributions.<br>
**Solution:** Proposed an AI-generated face image recognition method based on DualFace-RCSD (Dual-ResNet Face Real-Synthetic Cascaded Detector). This approach utilizes parallel ResNet50 networks as the backbone to process images separately after MTCNN face detection and the original images. It then fuses the confidence scores and multi-dimensional features from the predictions of both ResNet50 networks, ultimately employing a decision tree for precise identification of AI-generated faces.<br>
**Achievement:** National Second Prize in the Global Campus AI Algorithm Elite Challenge.<br>

⚡ **( IV)  Project 4:** ```Joint Decision-Making for Crop Planting and Sales Based on a Multi-Objective Stochastic Programming Model``` (Project Lead) (September 2024).<br>
**Task:** To address the crop planting optimization problem in rural North China, with key challenges including the uncertainty of price fluctuations, complex inter-crop relationships, and balancing long-term risk management.<br>
**Solution:** Developed a multi-objective stochastic programming model, integrating Monte Carlo simulation with the NSGA-II algorithm to determine optimal planting strategies that balance profitability and risk.<br>
**Personal Contributions:** Responsible for modeling and framework construction, writing sections on model and result analysis, visualization, and programming the penalty function patching.<br>
**Achievement:** Hubei Provincial First Prize in the National College Student Mathematical Contest in Modeling.<br>

⚡ **( V ) Project 5:** ```Apple Recognition and Picking Point Localization Based on Residual Neural Network``` (Project Lead) (April 2024).<br>
**Task:** To address the challenges of apple recognition and localization for picking robots under conditions of occlusion, overlap, and light/shadow interference.<br>
**Solution:** Initially, apples were segmented using fuzzy clustering. Subsequently, an improved Canny edge detection algorithm was utilized for localization. Finally, the images were transformed into the HSV color space for classification using ResNet50.<br>
**Personal Contributions:** Responsible for modeling and framework construction, writing sections on model and result analysis, visualization, and programming the fuzzy clustering and ResNet50 implementation.<br>
**Achievement:** International First Prize (Outstanding Winner equivalent) in the Asia-Pacific Mathematical Contest in Modeling.<br>

⚡ **( VI ) Project 6:** ```Poverty Data Mining and Relative Poverty Identification under Big Data``` (Core Team Member).<br>
**Task:** To address the multi-dimensional complexity of relative poverty identification and establish a scientific identification system for precise classification.<br>
**Solution:** Constructed a multi-dimensional poverty-revitalization synergistic indicator system, performed feature selection based on Random Forest, and utilized a Bayesian cost-sensitive neural network for identification.<br>
**Personal Contributions:** Responsible for modeling and framework construction, writing sections on preprocessing, model, and result analysis, visualization, and programming the feature selection implementation.<br>
**Achievement:** First Prize in the Central South Regional Competition of the China Collegiate Computer Design Contest.<br>

### III. Future Plans
🌱 I plan to delve deeply into the frontiers of Artificial Intelligence during my doctoral studies. Given the current trend of high interdisciplinary integration among AI branches, I aim to maintain an open mind to actively learn and explore various directions, including but not limited to Machine Learning Theory, Computer Vision, Natural Language Processing, Large Model Alignment or Lightweighting, Embodied Intelligence, and Large Model Safety. I aim to identify a specific research topic that ignites my passion.<br>
🌱 My current research interests are particularly focused on directions built upon a solid foundation of theoretical derivation, that can be closely integrated with deep learning models, and ultimately have clear vertical application scenarios. I aspire to explore the fundamental principles of intelligent behavior through rigorous mathematical modeling and theoretical analysis. Furthermore, I am committed to applying these theoretical insights to enhance existing deep learning algorithms' performance, interpretability, or generalization capabilities. For instance, my current exploration involves leveraging manifold geometry to approximate optimal transport for multi-modal time series alignment. Through this, I hope to uncover the intrinsic nature of how neural networks learn distributions and topological structures, and even investigate whether this approach can address the "shallow alignment" problem in large model safety, as well as how to discover multiple research problems and develop various models stemming from optimal transport theory.

### IV. Contact Information
Phone: 13534926288
Email: whutzwj@163.com

