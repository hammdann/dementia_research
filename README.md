**Overview**

Dementia is a growing public health challenge, with early detection and accurate prediction of disease progression critical for improving patient outcomes and optimizing healthcare resources. Current clinical tools often fail to identify subtle early symptoms and lack applicability across diverse populations, limiting timely interventions.

This project addressed these gaps by developing an interpretable predictive model that combined neuropsychological test results with MRI data. By leveraging machine and deep learning techniques, the model was able to estimate individual risk of dementia and assess the relative performance of different algorithms.

**Results**

Multimodal models consistently outperformed unimodal approaches across all algorithms. Models were evaluated across different subgroups, with SVM showing the largest improvement in F1-score (from 0.765 to 0.898, a 17% gain). CatBoost and FeedForward Neural Network also benefited from multimodal input, improving their F1-scores by 4% each. These results highlight the added predictive value of integrating neuropsychological and imaging data.

**Notebook and Table Structures**

Data were organised using schemas, tables, and volumes within the platform. Without the correct structure of the datasets, the code will produce errors and cannot be executed.

