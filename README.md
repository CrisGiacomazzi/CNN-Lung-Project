# CNN-Lung-Project

Cristiane Mecca Giacomazzi (Data Analyst)

This project was developed with Cross-industry standard process for data mining (CRISP-DM) methodology.

The following topics will be presented:

1. Business Understanding
2. Data Understanding
3. Ethical Statements
4. Data Preparation
5. Libraries used for this project
6. Project plan
7. Metrics
8. Communication and Action
9. References

**1. Business Understanding**

The chest X-ray is one of the most commonly used imaging tools for diagnosing lung diseases. It provides essential information about lung conditions at a low cost.  

Artificial intelligence (AI), especially a type of AI called deep learning, can accurately interpret and identify abnormal findings on chest X-rays. These AI systems often perform as well as or even better than radiologists, helping improve diagnostic accuracy.  

Deep learning models, such as convolutional neural networks (CNNs), are excellent at recognizing patterns in images. Using AI to analyze X-rays can have several advantages.  For a hospital, adopting deep learning models for X-ray analysis offers several benefits:  

- Cost Savings: Automating the analysis of X-rays reduces the time and expense of manual interpretation by radiologists, making the process more efficient.  
- Early Detection: AI can identify abnormalities earlier, potentially lowering treatment costs by preventing disease progression.  
- Better Resource Use: By quickly processing large numbers of X-rays, AI allows radiologists to focus on more complex cases, optimizing resource allocation.  
- Improved Patient Care: Faster and more accurate diagnoses lead to better outcomes, reducing the need for extra tests and treatments.  
- Scalability: Deep learning models can handle large datasets, making them ideal for widespread use in healthcare systems, which can save money on a larger scale.

<img width="451" alt="Screen Shot 2024-12-08 at 7 33 00 PM" src="https://github.com/user-attachments/assets/f3484282-2742-4818-a7b7-c072b4091cd7">

Image by Anderson (2024). Performance by physician specialty. Average AUC for radiologists, emergency medicine physicians, family medicine physicians, and internal medicine physicians when unaided (red) and aided (blue) by the AI system. Error bars represent 95% confidence intervals calculated using bootstrap sampling (m = 1000).

**2. Data Understanding**

The X-ray images used in this project can be found in this [link](https://data.mendeley.com/datasets/9d55cttn5h/1), a public dataset from Mendeley Data. 
- Total Number of Images: The dataset comprises a total of 3,475 X-ray images.

Classes within the Dataset:
- Normal (1250 Images): These images represent healthy lung conditions, serving as a reference for comparison in diagnostic procedures.
- Lung Opacity (1125 Images): This class includes X-ray images depicting various degrees of lung abnormalities, providing a diverse set of cases for analysis.
- Viral Pneumonia (1100 Images): Images in this category are associated with viral pneumonia cases.

**3. Ethical Statements**

For this project, it was used a public dataset from [Mendeley Data](https://data.mendeley.com/datasets/9d55cttn5h/1).

**4. Data preparation**

There was no necessity to prepare the dataset. It used the Convolutional Neural Networks algorithm, consisting of multiple layers. Each layer with a function, generating an output at the end of the process. 

**5. Libraries used for this project**

<img width="642" alt="Screen Shot 2024-12-08 at 7 36 06 PM" src="https://github.com/user-attachments/assets/cba56b7e-ce00-4028-9185-3eb9e86f129a">

**6. Project plan**

In this project, a CNN model was implemented to classify images into different classes using Python and TensorFlow. ChatGPT was used as a resource to generate initial versions of code snippets, provide troubleshooting advice, and optimize the machine learning pipeline.

<img width="658" alt="Screen Shot 2024-12-08 at 7 36 47 PM" src="https://github.com/user-attachments/assets/15c16884-8dfc-4816-97d6-9782e68bbf17">

Figure depicts the CNN steps. Image by author.

**7. Metrics**

<img width="292" alt="Screen Shot 2024-12-08 at 8 06 20 PM" src="https://github.com/user-attachments/assets/af334e56-5b40-4c1f-813f-807c51d1069f">

**8. Communication and Action**

The high training accuracy shows the model fits the training data well.
The drop from training to validation accuracy suggests mild overfitting, where the model may have learned specific details from the training data that don't generalize well to new data.
The high test accuracy indicates that the model's generalization has improved, meaning the training and validation processes likely succeeded in creating a robust model.
Furthermore, it is possible to consider techniques like dropout to improve generalization further.

**9. References**

Anderson, P. G., Tarder-Stoll, H., Alpaslan, M., Keathley, N., Levin, D. L., Venkatesh, S., Bartel, E., Sicular, S., Howell, S., Lindsey, R. V., & Jones, R. M. (2024). Deep learning improves physician accuracy in the comprehensive detection of abnormalities on chest X-rays. Scientific reports, 14(1), 25151. https://doi.org/10.1038/s41598-024-76608-2 

Guo, J., Li, Y., Wu, H. et al. Innovative chest X-ray image recognition technique and its economic value. Pers Ubiquit Comput 27, 1551–1559 (2023). https://doi.org/10.1007/s00779-021-01627-z 

Jones, C. M., Danaher, L., Milne, M. R., Tang, C., Seah, J., Oakden-Rayner, L., Johnson, A., Buchlak, Q. D., & Esmaili, N. (2021). Assessment of the effect of a comprehensive chest radiograph deep learning model on radiologist reports and patient outcomes: a real-world observational study. BMJ open, 11(12), e052902. https://doi.org/10.1136/bmjopen-2021-052902 

Kabiraj, A., Meena, T., Reddy, P.B., Roy, S. (2022). Detection and Classification of Lung Disease Using Deep Learning Architecture from X-ray Images. In: Bebis, G., et al. Advances in Visual Computing. ISVC 2022. Lecture Notes in Computer Science, vol 13598. Springer, Cham. https://doi.org/10.1007/978-3-031-20713-6_34 
Sahoo, P., Sharma, S. K., Saha, S., Jain, D., & Mondal, S. (2024). A multistage framework for respiratory disease detection and assessing severity in chest X-ray images. Scientific reports, 14(1), 12380. https://doi.org/10.1038/s41598-024-60861-6 

Yasaka, K., & Abe, O. (2018). Deep learning and artificial intelligence in radiology: Current applications and future directions. PLoS medicine, 15(11), e1002707. https://doi.org/10.1371/journal.pmed.1002707 

Zhang, H., Qie, Y. (2023). Applying Deep Learning to Medical Imaging: A Review.  Appl. Sci. 13(18), 10521. https://doi.org/10.3390/app131810521 

















