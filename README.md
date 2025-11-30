## Tainan Parking Space Prediction Model

#### Document
The complete report can be obtained from [Google Drive](https://drive.google.com/file/d/1QvEfjMdlYaCt-px-ulqjQziU7rIvjnGH/view?usp=share_link).

#### Introduction  
This study focuses on predicting parking space availability in Tainan City by integrating
weather forecast data, historical parking usage records, and national holiday information. We
formulate the task as both a regression problem—predicting the number of available parking
spaces—and a classification problem—predicting whether parking is available or nearly full. We
perform extensive data preprocessing, feature engineering, feature selection (Elastic Net and
ensemble-based voting), and model comparison across linear models, tree-based methods, and
Graph Neural Networks (GNNs). To address severe class imbalance in full-capacity cases, we
apply SMOTE and cost-sensitive learning. Our results demonstrate that the proposed approach
can provide practically useful predictions for both individual users and parking operators, and
has the potential to be integrated into smart city traffic management systems.

#### Collaborators
Fan-Jia Huang, Hung-Kai Yang, Hao-En Sun, Yi-Lun Hung, and Ching-Lin Chen.
