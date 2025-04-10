# IP-CRR: Information Pursuit for Interpretable Classification of Chest Radiology Reports

### Abstract
The development of AI-based methods for analyzing radiology reports could lead to significant advances in medical diagnosis, from improving diagnostic accuracy, to enhancing efficiency and reducing workload. However, the lack of interpretability of these methods has hindered their adoption in clinical settings. In this paper, we propose an interpretable-by-design framework for classifying radiology reports. The key idea is to extract a set of most informative queries from a large set of reports and use these queries and corresponding answers to predict a diagnosis. Thus, the explanation for the prediction is, by construction, the set of selected queries and their answers. We use the Information Pursuit framework to select the set of informative queries, the Flan-T5 model to answer them to verify if certain facts are present in the report, and a classifier to predict a disease from the selected queries and answers. Experiments on the MIMIC-CXR dataset show the effectiveness of the proposed method, highlighting its potential to enhance trust and usability in medical AI. 



