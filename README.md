# Network Intrusion Detection Using Various Deep Learning Approaches
Project By: Kamila Bekshentayeva, Matthew Canute, Young-min Kim, Donggu Lee, Adriena Wong

Network Intrusion Detection systems (NIDS), which are primary defence elements in the security of network technology, monitor network traffic in order to detect malicious activities. These systems rely on the identification of known attack signatures; however, the frequency of complex, diverse, and challenging-to-detect attacks increases the difficulty to identify current threats. Finding deviations from normal behaviour in the observed network traffic is known as anomaly-based intrusion detection.

In this paper, we compared the performance, based on the accuracy and F1 score, of three different machine learning models in their ability to detect network attacks: Feed Forward Neural Networks (FFNN), Long Short-Term Memory Networks (LSTM), and Echo State Networks (ESN). We used a simple two-layer FFNN, which did not directly take into account the temporal aspect of the data, and compared it to an LSTM and ESN, which are different types of recurrent neural networks (RNNs) that process sequential data. These models were chosen because of their success with the similar KDD data set. The three models were trained and tested on CSE-CIC-IDS2018 data set. Additionally, we tested the models’ performance on a modified attack to evaluate their adaptability.

Final Project Report:
[final_report.pdf](https://github.com/atwong88/NetworkIntrusionDetection/files/5468292/final_report.pdf)

Presentation Poster:
[final_poster.pdf](https://github.com/atwong88/NetworkIntrusionDetection/files/5468291/final_poster.pdf)

Dataset Sources: https://www.unb.ca/cic/datasets/index.html

