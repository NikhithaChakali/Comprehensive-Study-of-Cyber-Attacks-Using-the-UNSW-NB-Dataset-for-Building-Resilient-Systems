# Comprehensive-Study-of-Cyber-Attacks-Using-the-UNSW-NB-Dataset-for-Building-Resilient-Systems
## Overview
This project presents an in-depth exploratory data analysis (EDA) of the UNSW-NB cybersecurity dataset, aiming to uncover patterns in network traffic and attack behaviors to support the development of resilient systems. By analyzing key features such as Log Source, Protocol, Packet Type, and Attack Type, we gain insights into the nature and frequency of cyber threats, particularly those targeting firewalls and servers.
## Objectives
- Understand the distribution and characteristics of different cyber attack types.
- Identify dominant sources and protocols associated with malicious traffic.
- Visualize trends in packet behavior and traffic types.
- Provide actionable insights for strengthening network defenses.
## Tools & Libraries
- Python
- Pandas for data manipulation
- NumPy for numerical operations
- Matplotlib & Seaborn for data visualization
- UNSW-NB15 Dataset (CSV format)
## Data Preprocessing
- Checked for missing values and duplicates
- Imputed missing values using mean substitution
- Verified categorical distributions and feature uniqueness
## Exploratory Data Analysis (EDA)
Key visualizations include:
- Log Source Distribution: Firewall logs show slightly higher attack frequency than server logs.
- Protocol Analysis: Three protocol classes with balanced representation.
- Packet Type: Control packets dominate over data packets.
- Attack Type & Traffic Type: Diverse attack categories actively present.
- Packet Length Trends: Control packets tend to have longer lengths; Log Source impacts packet size.
## Insights
- Firewall attacks are more prevalent, suggesting a need for enhanced perimeter security.
- Control packets are more frequent, possibly indicating reconnaissance or command/control activity.
- Balanced protocol usage implies attackers exploit multiple layers of the network stack.
- Attack diversity highlights the importance of multi-layered defense strategies.
## Conclusion
This analysis provides a foundational understanding of cyber attack patterns within the UNSW-NB dataset. The insights can guide threat modeling, intrusion detection system (IDS) tuning, and policy formulation for network security teams. Future work may include feature engineering, machine learning classification, and real-time anomaly detection.

