## Literature Review (Chapter 2): Theoretical Foundations

### 2.1 Smart Building Management

**2.1.1 Definition and Concept of Smart Building**  
Smart buildings integrate advanced technologies, including IoT, wireless sensor networks, and intelligent management systems, to optimize energy consumption, comfort, and operational efficiency. These buildings rely on interconnected devices and automation to monitor and control various subsystems such as lighting, HVAC, and security, ensuring efficient resource use and improved occupant experiences[4].

**2.1.2 Energy Consumption Challenges**  
Energy management in smart buildings is complex due to fluctuating demand, integration of renewables, and the need for real-time optimization. Recent studies highlight the importance of accurate load and renewable energy forecasting to stabilize energy supply and demand, especially as renewable sources introduce variability and uncertainty into the grid. Deep learning and machine learning models have shown promise in improving forecasting accuracy, enabling better energy balance and operational decisions[4][5].

**2.1.3 The Role of Energy Management Systems (EMS)**  
EMS in smart buildings leverage real-time data from distributed sensors and advanced analytics to monitor, predict, and optimize energy usage. These systems support decision-making by providing actionable insights for reducing energy waste, integrating renewable sources, and maintaining grid stability. Hybrid and ensemble machine learning models have demonstrated high robustness in energy demand forecasting, supporting the deployment of intelligent EMS in modern buildings[4][5].

---

### 2.2 Internet of Things (IoT)

**2.2.1 IoT Concept and Architecture**  
IoT in smart buildings refers to the deployment of interconnected sensors and actuators that collect, transmit, and process data to enable intelligent automation and control. The architecture typically includes edge devices, communication networks, and centralized management platforms, facilitating seamless integration and real-time responsiveness[2][6].

**2.2.2 IoT Communication Technologies**  
Selecting the right wireless communication technology is critical for efficient IoT deployment in smart buildings. A comparative analysis of ZigBee, LoRa, and NB-IoT reveals distinct strengths:

- **ZigBee** offers reliable communication for dense sensor networks over moderate distances, making it suitable for intra-floor connectivity.
- **LoRa** provides long-range, low-power communication, ideal for multi-floor or large-area coverage, though with some packet loss over distance.
- **NB-IoT** excels in urban environments, offering robust, long-range connectivity with minimal packet loss, supporting large-scale deployments in dense structures[2][6].

**2.2.3 LoRa and WiFi**  
LoRa technology enables scalable, low-power wireless networks that penetrate building structures and support diverse IoT applications. WiFi, while providing higher bandwidth, is less efficient for battery-powered, long-range sensor networks. The choice between LoRa and WiFi depends on application requirements such as range, power consumption, and data throughput[2][6].

---

### 2.3 Artificial Intelligence for Smart Building Energy Optimization

**2.3.1 The Role of AI in Smart Building**  
AI enhances smart building operations by analyzing large volumes of sensor data to forecast energy demand, optimize resource allocation, and automate system responses. Machine learning (ML) and deep learning (DL) models, such as CNNs and LSTMs, have demonstrated superior performance in predicting energy consumption and managing complex building systems[4][5].

**2.3.2 Transformer Models**  
Transformer-based models have emerged as state-of-the-art for time series forecasting in energy systems. They efficiently capture temporal dependencies and nonlinear relationships in energy consumption data, outperforming traditional ML approaches. Studies show that transformer models, when applied to building energy forecasting, yield more accurate and transferable predictions, supporting proactive energy management[3][14][16].

**2.3.3 Temporal Fusion Transformer (TFT)**  
The Temporal Fusion Transformer (TFT) is a specialized deep learning architecture designed for multi-horizon time series forecasting. TFT combines attention mechanisms and recurrent structures, enabling it to handle mixed-type inputs and provide interpretable predictions. Recent research demonstrates TFT’s effectiveness in forecasting building energy loads, supporting advanced EMS and facilitating integration with renewable sources for improved grid stability[9][10][15][19].

---

## References

1. "Comparative analysis of ZigBee, LoRa, and NB-IoT in a smart building," International Journal of Reconfigurable and Embedded Systems, 2025[2][6].
2. "Zero-shot Load Forecasting for Integrated Energy Systems: A Large Language Model-based Framework with Multi-task Learning," arXiv, 2025[3].
3. "Systematic Review of Deep Learning and Machine Learning for Building Energy," Frontiers in Energy Research, 2022[4].
4. "Load and Renewable Energy Forecasting Using Deep Learning for Grid Stability," arXiv, 2025[5].
5. "Transfer Learning on Transformers for Building Energy Consumption Forecasting – A Comparative Study," 2024[14].
6. "Forecasting Energy Consumption of a Public Building Using Transformer and Support Vector Regression," 2023[16].
7. "An early prediction model on systemic risk using FinBERT and TFT in multimodal data fusion," 2025[9].
8. "Multi-Sensor Temporal Fusion Transformer for Stock Performance Prediction: An Adaptive Sharpe Ratio Approach," 2025[10].
9. "Significant of Blood Glucose Time-Series Forecasting with TFT Model for Type 1 Diabetes," 2024[15].
10. "Temporal Fusion Transformers for Streamflow Prediction: Value of Combining Attention with Recurrence," arXiv, 2023[19].

Would you like a more detailed explanation for any specific subsection or more references for your literature review?

Citations:
[1] https://pplx-res.cloudinary.com/image/private/user_uploads/14031542/a007f508-cb77-4e79-b481-68ec8939f42c/image.jpg
[2] https://ijres.iaescore.com/index.php/IJRES/article/view/21041
[3] https://arxiv.org/html/2502.16896v1
[4] https://www.frontiersin.org/journals/energy-research/articles/10.3389/fenrg.2022.786027/full
[5] https://arxiv.org/abs/2501.13412
[6] https://ijres.iaescore.com/index.php/IJRES/article/download/21041/pdf
[7] https://www.robustel.com/smart-cities/smart-building-management-via-lorawan-solution/
[8] https://www.themoonlight.io/en/review/ltpnet-integration-of-deep-learning-and-environmental-decision-support-systems-for-renewable-energy-demand-forecasting
[9] https://www.frontiersin.org/journals/energy-research/articles/10.3389/fenrg.2023.1292204/full
[10] https://www.taylorfrancis.com/chapters/edit/10.1201/9781003356639-2/recent-advancements-artificial-intelligence-machine-learning-sustainable-energy-management-chiranjit-biswas-abanishwar-chakraborti-swanirbhar-majumder
[11] https://core.ac.uk/reader/642655426
[12] https://www.themoonlight.io/en/review/zero-shot-load-forecasting-for-integrated-energy-systems-a-large-language-model-based-framework-with-multi-task-learning
[13] https://www.academia.edu/79543668/Machine_Learning_and_Deep_Learning_in_Energy_Systems_A_Review
[14] https://easychair.org/publications/preprint/tHDj
[15] https://www.thethingsindustries.com/news/smart-building-automation-systems-with-lorawan/
[16] https://arxiv.org/abs/2410.15286
[17] https://www.semanticscholar.org/paper/Electricity-Price-and-Load-Forecasting-using-Neural-Zahid-Ahmed/84a218b92024c2a806490e517f9fc56984b3b7f1
[18] https://www.linkedin.com/pulse/7-emerging-trends-ai-machine-learning-energy-iau8e
[19] https://orcid.org/0009-0004-3832-2512
[20] https://sinta.kemdikbud.go.id/journals/detail?id=8332
[21] https://scholar.google.co.id/citations?user=7WI1MiEAAAAJ

---

Answer from Perplexity: pplx.ai/share
