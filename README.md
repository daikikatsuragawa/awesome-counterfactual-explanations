# awesome-counterfactual-explanations

This repository is a curated collection of information (keywords, papers, libraries, books, etc.) about counterfactual explanations.

## Counterfactual Explanations

Counterfactual explanation is a method for calculating examples of perturbations of features that make different decisions with respect to the predictions of the current machine learning model. 
It is expressed in the form of "If it were X, it would be Y". 
This helps answer the question, "What would the outcome have been if some of my characteristics had been different?". 
Such explanations are useful in designing means and measures to overcome the current situation and in decision-making.

## Keywords

The following keywords are related to counterfactual explanations.

|  Keyword  |  Abstract  |
| ---- | ---- |
|  Explainable AI (XAI)  |  Also written as eXplainable AI. A generic term for methods and models used to help humans understand the behavior and predictions of machine learning systems, or related technologies and research fields.
|  Decision-Making  |  One of the motivations for using machine learning models. In addition to the predictions of traditional machine learning models, the use of Explainable AI and counterfactual hypothetical explanations is expected to support more decision-making.  |
|  Feature Attribution  |  Methods for calculating the contribution of each feature to the output of the model (LIME, SHAP, etc.). Sometimes compared to counterfactual explanations. |
|  Individual Conditional Expectation (ICE)  |   A method of measuring the change in predictions when a certain feature is varied.  |
|  Local Interpretable Model-agnostic Explanations (LIME)  |  A method of approximating machine learning models with locally interpretable models to explain individual predictions.  |
|  SHapley Additive exPlanations (SHAP) |  A method for calculating and explaining the contribution of each feature to the prediction to the outcome.  |

## Papers

- [Counterfactual Explanation Trees: Transparent and Consistent Actionable Recourse with Decision Trees](https://proceedings.mlr.press/v151/kanamori22a.html)
  - Authors: Kentaro Kanamori, Takuya Takagi, Ken Kobayashi, Yuichi Ike
  - Proceedings: Proceedings of The 25th International Conference on Artificial Intelligence and Statistics (2022)

- [Counterfactual explanations and how to find them: literature review and benchmarking](https://dl.acm.org/doi/abs/10.1145/3510457.3513081)
  - Author: Riccardo Guidotti
  - Article: Data Mining and Knowledge Discovery (2022)

- [Counterfactual Explanations for Models of Code](https://link.springer.com/article/10.1007/s10618-022-00831-6)
  - Authors: Jürgen Cito, Isil Dillig, Vijayaraghavan Murali, Satish Chandra
  - Proceedings: Proceedings of the 44th International Conference on Software Engineering: Software Engineering in Practice (2022)

- [Counterfactuals and causability in explainable artificial intelligence: Theory, algorithms, and applications](https://www.sciencedirect.com/science/article/abs/pii/S1566253521002281)
  - Authors: Yu-Liang Chou, Catarina Moreira, Peter Bruza, Chun Ouyang, Joaquim Jorge
  - Article: Information Fusion (2022)

- [A Survey of Contrastive and Counterfactual Explanation Generation Methods for Explainable Artificial Intelligence](https://ieeexplore.ieee.org/abstract/document/9321372)
  - Authors: Ilia Stepin, Jose M. Alonso, Alejandro Catala, Martín Pereira-Fariña
  - Article: IEEE Access (2021)

- [Algorithmic Recourse: from Counterfactual Explanations to Interventions](https://dl.acm.org/doi/10.1145/3442188.3445899)
  - Authors: Amir-Hossein Karimi, Bernhard Schölkopf, Isabel Valera
  - Proceedings: Proceedings of the 2021 ACM conference on fairness, accountability, and transparency (2021)

- [Counterfactual Explainable Recommendation](https://dl.acm.org/doi/abs/10.1145/3459637.3482420)
  - Authors: Juntao Tan, Shuyuan Xu, Yingqiang Ge, Yunqi Li, Xu Chen, Yongfeng Zhang
  - Proceedings: Proceedings of the 30th ACM International Conference on Information &amp; Knowledge Management (2021)

- [Counterfactual Explanations Can Be Manipulated](https://www.hbs.edu/faculty/Pages/item.aspx?num=61912)
  - Authors: Dylan Slack, Sophie Hilgard, Himabindu Lakkaraju, Sameer Singh
  - Proceedings: Neural Information Processing Systems (2021)

- [Counterfactual Explanations for Neural Recommenders](https://dl.acm.org/doi/abs/10.1145/3404835.3463005)
  - Authors: Khanh Hiep Tran, Azin Ghazimatin, Rishiraj Saha Roy 
  - Proceedings: Proceedings of the 44th International ACM SIGIR Conference on Research and Development in Information Retrieval (2021)

- [DECE: Decision Explorer with Counterfactual Explanations for Machine Learning Models](https://ieeexplore.ieee.org/document/9229232)
  - Authors: Furui Cheng, Yao Ming, Huamin Qu
  - Article: IEEE Transactions on Visualization and Computer Graphics (2020)

- [Evaluating the Quality of Machine Learning Explanations: A Survey on Methods and Metrics](https://www.mdpi.com/2079-9292/10/5/593)
  - Authors: Jianlong Zhou, Amir H. Gandomi, Fang Chen, Andreas Holzinger 
  - Article: Electronics (2021)

- [Explaining Explanations in AI](https://dl.acm.org/doi/10.1145/3287560.3287574)
  - Authors: Brent Mittelstadt, Chris Russell, Sandra Wachter
  - Proceedings: Proceedings of the Conference on Fairness, Accountability, and Transparency (2021)

- [Interpretable Counterfactual Explanations Guided by Prototypes](https://dl.acm.org/doi/abs/10.1007/978-3-030-86520-7_40)
  - Authors: Arnaud Van Looveren , Janis Klaise
  - Proceedings: Machine Learning and Knowledge Discovery in Databases. Research Track: European Conference, ECML PKDD 2021, Bilbao, Spain, September 13–17, 2021, Proceedings, Part III (2021)

- [Ordered Counterfactual Explanation by Mixed-Integer Linear Optimization](https://ojs.aaai.org/index.php/AAAI/article/view/17376)
  - Authors: Kentaro Kanamori, Takuya Takagi, Ken Kobayashi, Yuichi Ike, Kento Uemura, Hiroki Arimura
  - Proceedings: Proceedings of the AAAI Conference on Artificial Intelligence (2021)

- [The Skyline of Counterfactual Explanations for Machine Learning Decision Models](https://dl.acm.org/doi/10.1145/3459637.3482397)
  - Authors: Yongjie Wang, Qinxu Ding, Ke Wang, Yue Liu, Xingyu Wu, Jinglong Wang, Yong Liu, Chunyan Miao
  - Proceedings: Proceedings of the 30th ACM International Conference on Information &amp; Knowledge Management (2021)

- [The Use and Misuse of Counterfactuals in Ethical Machine Learning](https://dl.acm.org/doi/10.1145/3442188.3445886)
  - Authors: Atoosa Kasirzadeh, Andrew Smart
  - Proceedings: Proceedings of the 2021 ACM Conference on Fairness, Accountability, and Transparency (2021)

- [Towards Unifying Feature Attribution and Counterfactual Explanations: Different Means to the Same End](https://dl.acm.org/doi/abs/10.1145/3461702.3462597)
  - Authors: Ramaravind Kommiya Mothilal, Divyat Mahajan, Chenhao Tan, Amit Sharma
  - Proceedings: Proceedings of the 2021 AAAI/ACM Conference on AI, Ethics, and Society (2021)

- [Transparent Dreams (Are Made of This): Counterfactuals as Transparency Tools in ADM](https://cal.library.utoronto.ca/index.php/cal/article/view/36283)
  - Author: Katja de Vries
  - Article: Critical Analysis of Law (2021)

- [DACE: Distribution-Aware Counterfactual Explanation by Mixed-Integer Linear Optimization](https://www.ijcai.org/proceedings/2020/395)
99
  - Authors: Kentaro Kanamori, Takuya Takagi, Ken Kobayashi, Hiroki Arimura
100
  - Proceedings: Proceedings of the Twenty-Ninth International Joint Conference on Artificial Intelligence (2020)
- [Explaining Machine Learning Classifiers through Diverse Counterfactual Examples](https://dl.acm.org/doi/abs/10.1145/3351095.3372850)
  - Authors: Ramaravind K. Mothilal, Amit Sharma, Chenhao Tan
  - Proceedings: Proceedings of the 2020 conference on fairness, accountability, and transparency (2020)

- [FACE: Feasible and Actionable Counterfactual Explanations](https://dl.acm.org/doi/abs/10.1145/3375627.3375850)
  - Authors: Rafael Poyiadzi, Kacper Sokol, Raul Santos-Rodriguez, Tijl De Bie, Peter Flach
  - Proceedings: Proceedings of the AAAI/ACM Conference on AI, Ethics, and Society (2020)

- [Good Counterfactuals and Where to Find Them: A Case-Based Technique for Generating Counterfactuals for Explainable AI (XAI)](https://dl.acm.org/doi/10.1007/978-3-030-58342-2_11)
  - Authors: Mark T. Keane, Barry Smyth
  - Proceedings: Case-Based Reasoning Research and Development: 28th International Conference, ICCBR 2020, Salamanca, Spain, June 8–12, 2020, Proceedings (2020)

- [Learning Model-Agnostic Counterfactual Explanations for Tabular Data](https://dl.acm.org/doi/abs/10.1145/3366423.3380087)
  - Authors: Martin Pawelczyk, Klaus Broelemann, Gjergji Kasneci
  - Proceedings: Proceedings of The Web Conference 2020 (2020)

- [Model-Agnostic Counterfactual Explanations for Consequential Decisions](https://proceedings.mlr.press/v108/karimi20a.html)
  - Authors: Amir-Hossein Karimi, Gilles Barthe, Borja Balle, Isabel Valera
  - Proceedings: International Conference on Artificial Intelligence and Statistics (2020)

- [Multi-Objective Counterfactual Explanations](https://link.springer.com/chapter/10.1007/978-3-030-58112-1_31)
  - Authors: Susanne Dandl, Christoph Molnar, Martin Binder, Bernd Bischl 
  - Proceedings: International Conference on Parallel Problem Solving from Nature (2020)

- [PRINCE: Provider-side Interpretability with Counterfactual Explanations in Recommender Systems](https://dl.acm.org/doi/abs/10.1145/3336191.3371824)
  - Authors: Azin Ghazimatin, Oana Balalau, Rishiraj Saha Roy, Gerhard Weikum
  - Proceedings: Proceedings of the 13th International Conference on Web Search and Data Mining

- [The hidden assumptions behind counterfactual explanations and principal reasons](https://dl.acm.org/doi/10.1145/3351095.3372830)
  - Authors: Solon Barocas, Andrew D. Selbst, Manish Raghavan
  - Proceedings: Proceedings of the 2020 Conference on Fairness, Accountability, and Transparency (2020)

- [ViCE: visual counterfactual explanations for machine learning models](https://dl.acm.org/doi/10.1145/3377325.3377536)
  - Authors: Oscar Gomez, Steffen Holter, Jun Yuan, Enrico Bertini
  - Proceedings: Proceedings of the 25th International Conference on Intelligent User Interfaces

- [Factual and Counterfactual Explanations for Black Box Decision Making](https://ieeexplore.ieee.org/document/8920138)
  - Authors: Riccardo Guidotti, Anna Monreale, Fosca Giannotti, Dino Pedreschi, Salvatore Ruggieri, Franco Turini
  - Article: IEEE Intelligent Systems (2019)

- [Counterfactual Explanations Without Opening the Black Box: Automated Decisions and the GDPR](https://heinonline.org/HOL/LandingPage?handle=hein.journals/hjlt31&div=29&id=&page=)
  - Authors: Sandra Wachter, Brent Mittelstadt, Chris Russell
  - Article: Harvard Journal of Law & Technology (2018)

## Books

- [Interpretable Machine Learning: A Guide For Making Black Box Models Explainable](https://www.amazon.co.jp/dp/B09TMWHVB4)
  - Author: Christoph Molnar
  - Also available on the web [[link](https://christophm.github.io/interpretable-ml-book/)]
  - About counterfactual explanations [[link](https://christophm.github.io/interpretable-ml-book/counterfactual.html)]

## Libraries

- [interpretml/DiCE](https://github.com/interpretml/DiCE)
  - Generates diverse counterfactual examples

- [SeldonIO/alibi](https://github.com/SeldonIO/alibi)
    - Generates counterfactuals guided by prototypes

- [andreArtelt/ceml](https://github.com/andreArtelt/ceml)
  - Toolbox for computing counterfactuals

- [pat-alt/CounterfactualExplanations.jl](https://github.com/pat-alt/CounterfactualExplanations.jl)
  - Implemented by Julia

## How to contribute

Please just update this README.md. The following updates are welcomed.

- Addition of information on counterfactual explanations
- Other (If necessary, we can discuss)
  - Discussion about adding new sections, etc.
