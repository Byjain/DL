Package Used:
pytorch 1.8.0
pandas 0.24.2

Datasets:
University of Maryland lithium battery dataset CALCE, lithium battery life prediction based on Python: https://snailwish.com/437/
NASA lithium battery data set, lithium battery life prediction based on Python: https://snailwish.com/395/

Parameters:
Model has six key parameter: sampler size (m), learning rate (τ ), depth (l) and hidden size (s) of Transformer, regularization for learning (λ), and ratio of each task (α). m can be set about 5∼10% of the length of a sequence. In experiments, m is fixed at 16 and 64 for NASA and CALCE, respectively.

Description:
Battery life cycle prediction faces significant hurdles due to the unconventional battery degradation process and limited data availability. The nonlinear deterioration pattern of batteries, characterized by minimal capacity loss in early stages followed by rapid decline later, complicates early-stage forecasting. This nonlinearity poses a substantial challenge for prediction models. The scarcity of comprehensive battery datasets further compounds the problem. Acquiring such data is resource-intensive, involving costly and time-consuming cycling experiments. This data shortage impedes the development of robust prediction models and hinders research progress in the field. Another critical issue is the tendency of models to overfit when trained on limited datasets. While they may perform well on familiar data, these models often struggle to generalize to new, unseen battery information. This lack of adaptability is particularly problematic given the diverse range of lithium-ion battery chemistries, operating conditions, and degradation mechanisms. The variability in battery types and usage scenarios also impacts model generalizability. Models trained on specific battery configurations or conditions may fail to perform adequately when applied to different contexts. This limitation highlights the need for more versatile and adaptable prediction systems.

Following are the major contributions of this project:
1. Proposed a de-noising transformer based architecure for battery life cycle prediction
2. Analysed and compared the performance on NASA and CALCE battery dataset
3. Compared the performance with existing neural network based models in terms of MAE,
and RMSE.
