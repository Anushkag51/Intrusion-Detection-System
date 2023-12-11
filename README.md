# Intrusion-Detection-System
# Description
# Problem Statement
Information security has grown to be of the utmost importance in today's linked and digitalized society. Computer networks are essential for corporate operations, data sharing, and communication inside organizations and between individuals. However, because of this dependency, these networks are now vulnerable to a variety of cyberthreats and assaults that might compromise the confidentiality, integrity, and accessibility of private data.Bad actors try to break into systems to steal information or cause damage. To protect against this, we use something called an Intrusion Detection System (IDS). Think of it 
as a security guard for computers. 
# Objective
- Traditional IDS methods have some weaknesses. They might not catch new and tricky attacks. So, I have used a smarter way to do this using machine learning. Machine learning is like teaching computers to learn from examples.
- Goal in this project is to build a better IDS using machine learning i.e., to create a system that can learn the difference between normal computer behavior and strange, possibly harmful actions. By looking at lots of data from before, the system will learn what's normal. Then, it can recognize when something odd is happening.
# Dataset
This dataset is taken from Kaggle its name is LUFlow is a flow-based network intrusion detection data set, which contains a robust ground truth through correlation of malicious behavior of requests sent on the network. In this project, 4 datasets are taken from different dates which are as follows:
1. 08.07.2020
2. 20.01.21
3. 12.02.2021
4. 12.06.2022
   
They all have 16 columns which are
- Avg_ipt
- Bytes_in
- Bytes_out
- Dest_ip
- Dest_port
- Entropy
- Num_pkts_out
- Num_pkts_in
- Proto, Src_ip
- Src_port
- Time_end
- time_start
- total_entropy
- label
- duration
