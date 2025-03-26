## Chronic kidney disease prediction
A machine learning-based system for early and accurate prediction of kidney disease to improve diagnosis and patient outcomes.

## About
The **Intelligent Kidney Disease Prediction System** leverages machine learning techniques to detect kidney disease at an early stage, enabling timely intervention and better patient outcomes. The system analyzes key clinical parameters, including blood pressure, serum creatinine, hemoglobin, and albumin levels, to identify patterns associated with kidney disease. Advanced algorithms such as Logistic Regression, Random Forest, Neural Networks, and feature selection methods like Recursive Feature Elimination (RFE) ensure high accuracy in predictions.  

Designed to integrate seamlessly into clinical workflows, the system offers a user-friendly interface for healthcare professionals to input patient data and receive real-time diagnostic insights. The solution addresses the limitations of traditional diagnostic methods, which are often time-consuming and fail to detect the disease at its early stages. By focusing on predictive analytics, it reduces the burden of costly treatments such as dialysis or transplants.  

Scalable and cost-effective, this system can be deployed in various healthcare settings, including clinics and rural centers, making advanced diagnostics accessible to all. The project emphasizes improving healthcare efficiency and achieving global equity in kidney disease detection and management.
## Features
- Implements advanced machine learning algorithms like Logistic Regression, Random Forest, and Neural Networks.  
- Utilizes feature selection methods like Recursive Feature Elimination (RFE) for improved prediction accuracy.  
- A framework-based application for easy integration and deployment in clinical workflows.  
- High scalability and adaptability for diverse healthcare environments, including rural and urban centers.  
- Provides real-time predictions with minimal time complexity for faster diagnosis.  
- User-friendly interface for healthcare professionals to input patient data and retrieve diagnostic insights.  
- Cost-effective solution, reducing reliance on expensive late-stage treatments.  
- Supports explainable AI to enhance transparency and trust in predictions.  
- Ensures data privacy and security with robust handling of sensitive patient information.  

## Requirements
* **Operating System:** Requires a 64-bit OS (Windows 10, Windows 11, or Ubuntu) for compatibility with machine learning frameworks.  
* **Development Environment:** Python 3.7 or later for developing the kidney disease prediction system.  
* **Machine Learning Frameworks:** Scikit-learn for algorithm implementation and TensorFlow or PyTorch for advanced neural network models.  
* **Data Analysis Libraries:** Pandas and NumPy for data manipulation and preprocessing.  
* **Visualization Tools:** Matplotlib and Seaborn for data visualization and analysis of model performance.  
* **Version Control:** Git for collaborative development and efficient code management.  
* **IDE:** VSCode or PyCharm for coding, debugging, and integration.  
* **Additional Dependencies:** Includes SciPy, TensorFlow GPU (optional for enhanced performance), OpenCV (if image-based features are integrated), and Flask or Django for creating the web application interface.  
* **Hardware Requirements:** Minimum 8 GB RAM and a multi-core processor; GPU support is recommended for neural network training.  

## System Architecture
![image](https://github.com/user-attachments/assets/09ad8462-9a25-4591-8281-fac6b318be2b)


## Output


#### Output1 - Prediction of class using 1D CNN
![image](https://github.com/user-attachments/assets/e6ae62d0-99f3-4720-8deb-b3328a1e1986)


#### Output2 - Prediction of stage using RFA
![image](https://github.com/user-attachments/assets/986a4f46-b3e8-4317-b770-b5558e458cdf)

### Results

The hybrid model combining a 1D Convolutional Neural Network (CNN) and a Random Forest Algorithm (RFA) achieved notable results in chronic kidney disease (CKD) prediction and staging. The CNN model excelled in binary classification, demonstrating high accuracy, precision, recall, and F1 scores in identifying whether a patient has CKD or not. Its ability to extract patterns from the sequential features ensured reliable predictions in distinguishing CKD-positive from CKD-negative cases.

For stage classification, the RFA model significantly outperformed the CNN, achieving superior accuracy in predicting the severity of CKD across stages 1 to 5. By integrating the CNN’s classification output as an additional input feature, the RFA model leveraged this information to enhance stage-specific predictions, achieving balanced performance across all five stages. The combination of these models successfully addressed the challenges of binary and multiclass classification, offering an accurate and interpretable system for CKD diagnosis.

### Impact

This hybrid approach provides a reliable, data-driven solution for early detection and precise staging of CKD, critical for timely intervention and personalized treatment planning. The high accuracy of the CNN model ensures effective screening for CKD, enabling healthcare providers to identify at-risk patients early. Meanwhile, the RFA model’s robust stage classification supports clinicians in tailoring treatment plans based on disease severity, facilitating better disease management.

The integration of machine learning in CKD prediction has broader implications for healthcare, emphasizing the role of AI in enhancing diagnostic accuracy and decision-making. The hybrid model's ability to handle complex data and deliver actionable insights demonstrates its potential for real-world applications. This work contributes to the growing field of AI-assisted healthcare and paves the way for further advancements in automated disease detection and management.
## Articles published / References
[1] https://doi.org/10.3390/diagnostics12010116
[2] AJITH KUMAR C. HARI HARAN, D. MANU VIGNESH “Chronic
Kidney Disease Prediction using Random Forest Algorithm in Machine
Learning” International Journal of Innovative Science and Research
Technology Volume 7, Issue 2, February – 2022, ISSN No:- 2456-2165.
[3] Bin Zhang, MD, Chun-song Cheng, Ph.D., Min-gang Ye, MD, Chengzheng Han, MD, Dai-yin Peng, Ph.D. “A preliminary study of the effects
of medical exercise Wuqinxi on indicators of skin temperature, muscle
coordination, and physical quality” http://www.mdjournal.com/ Zhang
et al. Medicine (2018) 97:34.
[4] Ebrahime Mohammed Senan, Mosleh Hmoud Al-Adhaileh, Fawaz
Waselallah Alsaade, Theyazn H. H. Aldhyani, Ahmed Abdullah Alqarni,
Nizar Alsharif, M. Irfan Uddin, Ahmed H. Alahmadi, Mukti E Jadhav
and Mohammed Y. Alzahrani “Diagnosis of Chronic Kidney Disease
Using Effective Classification Algorithms and Recursive Feature Elimination Techniques” Journal of Healthcare Engineering Volume 2021,
Article ID 1004767, 10 pages
[5] Gabriel R. Vasquez-morales1, Sergio M. Mart ´ ´ınez-Monterrubio, Pablo
Moreno-Ger and juan A. Recio-Garc´ıa “Explainable Prediction of
Chronic Renal Disease in the Colombian Population Using Neural
Networks and Case-Based Reasoning” EEE Access · October 2019.
[6] Ramesh Chandra Poonia, Mukesh Kumar Gupta, Ibrahim Abunadi,
Amani Abdulrahman Albraikan, Fahd N. Al-Wesabi, Manar Ahmed
Hamza and Tulasi B “Intelligent Diagnostic Prediction and Classification
Models for Detection of Kidney Disease” Healthcare 2022, 10, 371.
[7] Randal K. Detwiler, Emily H. Chang, Melissa C. Caughey, Melrose W.
Fisher, Timothy C. Nichols, Elizabeth P. Merricks, Robin A. Raymer,
Margaret Whitford, Dwight A. Bellinger, Lauren E. Wimsey, Caterina
M. Gallippi [Member, IEEE] “Mechanical Anisotropy Assessment in
Kidney Cortex Using ARFI Peak Displacement: Preclinical Validation
and Pilot In Vivo Clinical Results in Kidney Allografts” IEEE Trans
Ultrason Ferroelectr Freq Control. 2019 March ; 66(3): 551–562.
doi:10.1109/ TUFFC.2018.2865203
[8] Dibaba Adeba Debal and Tilahun Melak Sitote “Chronic kidney disease
prediction using machine learning techniques” Debal and Sitote Journal
of Big Data (2022) 9:109.
[9] John W Stanifer, Bocheng Jing, Scott Tolan, Nicole Helmke, Romita
Mukerjee, Saraladevi Naicker, Uptal Patel “The epidemiology of chronic
kidney disease in sub-Saharan Africa: a systematic review and metaanalysis” Lancet Glob Health 2014; 2: e174–181.
[10] Diego Buenano-Fern ˜ andez, David Gil and Sergio Luj ´ an-Mora “Appli- ´
cation of Machine Learning in Predicting Performance for Computer
Engineering Students: A Case Study” Sustainability · May 2019.
[11] Dhanush, M., Hency, Raj., Pratik, Bothra., Raman, Zanwar., Dr


