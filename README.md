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

- [Counterfactual explanations and how to find them: literature review and benchmarking](https://link.springer.com/article/10.1007/s10618-022-00831-6)
  - Author: Riccardo Guidotti
  - Article: Data Mining and Knowledge Discovery (2022)

- [Algorithmic Recourse: from Counterfactual Explanations to Interventions](https://dl.acm.org/doi/10.1145/3442188.3445899)
  - Authors: Amir-Hossein Karimi, Bernhard Schölkopf, Isabel Valera
  - Proceedings: Proceedings of the 2021 ACM conference on fairness, accountability, and transparency (2021)

- [DECE: Decision Explorer with Counterfactual Explanations for Machine Learning Models](https://ieeexplore.ieee.org/document/9229232)
  - Authors: Furui Cheng, Yao Ming, Huamin Qu
  - Article: IEEE Transactions on Visualization and Computer Graphics (2020)

- [The Use and Misuse of Counterfactuals in Ethical Machine Learning](https://dl.acm.org/doi/10.1145/3442188.3445886)
  - Authors: Atoosa Kasirzadeh, Andrew Smart
  - Proceedings: Proceedings of the 2021 ACM Conference on Fairness, Accountability, and Transparency (2021)

- [Explaining Machine Learning Classifiers through Diverse Counterfactual Examples](https://dl.acm.org/doi/abs/10.1145/3351095.3372850)
  - Authors: Ramaravind K. Mothilal, Amit Sharma, Chenhao Tan
  - Proceedings: Proceedings of the 2020 conference on fairness, accountability, and transparency (2020)

- [FACE: Feasible and Actionable Counterfactual Explanations](https://dl.acm.org/doi/abs/10.1145/3375627.3375850)
  - Authors: Rafael Poyiadzi, Kacper Sokol, Raul Santos-Rodriguez, Tijl De Bie, Peter Flach
  - Proceedings: Proceedings of the AAAI/ACM Conference on AI, Ethics, and Society (2020)

- [Model-Agnostic Counterfactual Explanations for Consequential Decisions](https://proceedings.mlr.press/v108/karimi20a.html)
  - Authors: Amir-Hossein Karimi, Gilles Barthe, Borja Balle, Isabel Valera
  - Proceedings: International Conference on Artificial Intelligence and Statistics (2020)

- [Multi-Objective Counterfactual Explanations](https://link.springer.com/chapter/10.1007/978-3-030-58112-1_31)
  - Authors: Susanne Dandl, Christoph Molnar, Martin Binder, Bernd Bischl 
  - Proceedings: International Conference on Parallel Problem Solving from Nature (2020)

- [The hidden assumptions behind counterfactual explanations and principal reasons](https://dl.acm.org/doi/10.1145/3351095.3372830)
  - Authors: Solon Barocas, Andrew D. Selbst, Manish Raghavan
  - Proceedings: Proceedings of the 2020 Conference on Fairness, Accountability, and Transparency (2020)

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
