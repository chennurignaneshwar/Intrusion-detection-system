# Intrusion-detection-system


The proposed project aims to develop a Deep learning (DL) techniques that are being
widely researched for their effectiveness in detecting cyber intrusions against the Internet of
Things (IoT). However, time sensitive Critical Infrastructures (CIs) that rely on IoT require
quicker detection of cyber intrusions close to the constrained devices in order to prevent service
delays. FoG layer with higher computing resources and close proximity to IoT devices makes
them suitable to deploy deep learning techniques for effective intrusion detection. However,
communication overheads due to large volume of IoT data and computation requirements for
deep learning models prevents effective use of FoG layer and raises scalability issues.
To counter these issues, a novel on IoT intrusion detection framework incorporates
feature selection step on time-series IoT data, followed by a deep learning Recurrent Neural
Network (SimpleRNN or Bi-directional Long Short-Term Memory (LSTM)) based IoT attack
detection. The effectiveness of the proposed approach was evaluated using the highdimensional BoT-IoT dataset which contains large volumes of realistic IoT attack traffic. Results
show that feature selection methods significantly ( 90%) reduced the dataset size and still
achieved an increased recall rate compared to full feature set without loosing class
differentiation ability. The SimpleRNN and Bi-LSTM models also did not suffer any underfitting
or overfitting with the reduced feature space. The proposed deep learning based IoT intrusion
detection framework is suitable for FoG layer deployment and can scale well with effective use
of sub-divided dataset.

# Objectives:
1. Develop an IoT intrusion detection framework using deep learning techniques.
2. Incorporate feature selection on time-series IoT data to reduce data volume.
3. Deploy deep learning models (SimpleRNN and Bi-LSTM) for IoT attack detection.
4. Address scalability and communication overhead issues in processing large IoT datasets.

# Expected Outcomes:
1. Significant reduction (up to 90%) in dataset size while maintaining class differentiation
ability.
2. Improved recall rates compared to using the full feature set.
3. Scalable and effective intrusion detection with sub-divided datasets.
4. Models that avoid underfitting or overfitting with reduced feature spaces.
   
# Requirements:
• Hardware: Google Colab.
• Software: Python, TensorFlow or PyTorch, and other data visualization tools.
• Data: High-dimensional BoT-IoT dataset containing realistic IoT attack traffic. (.pcap
files) for training and testing.
• Techniques: Computational resources to train and deploy SimpleRNN and Bi-LSTM
models.
# Conclusion: 
This project aims to develop a scalable IoT intrusion detection framework using deep learning
models (SimpleRNN and Bi-LSTM) deployed on the FoG layer to enable quick and efficient detection of
cyber intrusions. It addresses communication overheads and scalability issues by incorporating feature
selection to reduce data size. The framework ensures effective intrusion detection for time-sensitive IoTbased critical infrastructures.
