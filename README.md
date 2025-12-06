## Welcome to Weijie Zhu's Homepage 😄😄
✨ I am an undergraduate student majoring in Information and Computational Science (Class of 2022) at Wuhan University of Technology. **I am on the postgraduate recommendation track this year** and possess a **strong aspiration to pursue doctoral studies!** <br>
✨ Research Skills: (1) **Strong practical skills and self-motivation.** I have extensive experience in reproducing deep learning projects and practical experience in data mining. I have independently studied the deployment and fine-tuning of large models and the construction of the MCP Server. Furthermore, I possess considerable experience in mathematical modeling (primarily as a modeler, with auxiliary programming and writing responsibilities). (2) **Solid research experience.** I have undergone one and a half years of comprehensive research training, enabling me to independently complete the entire research workflow, including deep learning framework construction, experimental design and implementation, visualization, academic paper writing, and submission. (3) **Theoretical derivation capabilities.** My current research focuses on deriving an approach that utilizes manifold geometry to approximate optimal transport for multimodal time series alignment, producing concise yet impactful work. (4) **English proficiency:** I have successfully passed CET-4 and CET-6, can write academic papers in English, and maintain a daily habit of reading English literature. The following section details my specific experiences: <br>


### I. Research Papers
**💬 ( I ) Journal Paper:** SCI Q1, Expert Systems with Applications, Independent First Author, **under minor revision**<br>
**GHOST: Sentiment-gated Mamba and Stock-wise Tokenization for Enhanced Stock Prediction** <be>
**Pain Points:** <br>
**( i )** Current sentiment analysis methods exhibit **insufficient** market sentiment quantification and **lack** dynamic adaptive integration mechanisms for market fluctuations.<br>
**( ii )** Transformer-based models' quadratic complexity **limits** long-term stock prediction while **lacking** finance-specific temporal inductive biases.<br>
**( iii )** Traditional temporal tokenization paradigms forcibly merge multi-stock features, **weakening** stock correlation modeling while dramatically increasing computational costs.<br>
**Innovations:** <br>
**( i )** Extracting comprehensive market sentiment representations from massive sentiment-analyzed news (polarity, volume, and distribution features), and implementing a **Hierarchical Sentiment-gating Layer** for dynamic adaptive integration of affective features with trading data.<br>
**( ii )** Dynamically parameterized **Intra-Stock Mamba Selection Layer** introduces specialized financial inductive biases with time-series linear complexity<br>
**( iii )** **Stock-wise Tokenization Layer** converts temporal tokens into stock tokens preserving sequence integrity, and **Inter-Stock Attention Layer** captures market correlations via attention between stock tokens while reducing complexity from temporal sequence ( $O(T^2)$ ) to stock quantity ( $O(N^2)$ ) where $N \ll T$.<be>
**Future Work:** Exploring the derivation of manifold geometry to approximate optimal transport for aligning sentiment data and stock data, to generalize to multi-modal time series alignment.<br>
**Personal Contributions:** Model construction, experimental design and implementation, visualization, and manuscript writing.<br>
```Project Link:``` https://github.com/WHUT-zwj/GHOST <br>

**💬 ( II ) Conference Paper:** CCF B, European Conference on Artificial Intelligence (ECAI), Second Author, **Accepted**<br>
**LAMM-ViT: AI Face Detection via Layer-Aware Modulation of Region-Guided Attention**<be>
**Pain Points:** <br>
**( i )** Existing detection methods exhibit **insufficient** generalization capabilities against novel generative techniques, often **over-relying** on superficial artifacts rather than deep structural flaws.<br>
**( ii )** Traditional attention mechanisms **lack** cross-layer dynamic adjustment capabilities, making it difficult to effectively capture the hierarchical and regional inconsistencies characteristic of forged faces.<br>
**( iii )** Advanced generative models have inherent **limitations** in maintaining subtle structural correlations between facial regions, a weakness not yet fully exploited.<be>
**Innovations:** <br>
**( i )** Proposed **Region-Guided Multi-Head Attention (RG-MHA)**, which utilizes facial keypoints to precisely guide the model to focus on structural inconsistencies between regions.<br>
**( ii )** Introduced **Layer-Aware Mask Modulation (LAMM)**, enabling dynamic adjustment of regional attention across network depths to capture multi-level forgery features.<br>
**( iii )** Designed a **Mask Diversity Loss (Ldiv)** to incentivize the model to learn diverse detection strategies, enhancing generalization performance against unknown generative techniques.<br>
**Personal Contributions:** Methodology writing, visualization, and assisting with comparative experiments.<br>


### II. Contact Information
Phone: 13534926288
Email: whutzwj@163.com

