# Vehicle-Insurance-Fraud-Detection
A Hybrid Approach for Detecting Vehicle Insurance  Fraud Using Data Balancing and Deep Learning  Techniques with Explainable AI 

Insurance fraud is a growing concern in the industry, leading to significant financial losses. Detecting fraudulent claims, especially in vehicle insurance, is challenging due to the rarity of such cases and the complexity of available data.  
 
The primary issues involve severe class imbalance in structured data and the difficulty in interpreting and verifying fraud predictions, particularly with unstructured image data.  
 
This project focuses on identifying fraudulent claims using both structured (tabular) data and unstructured (image) data through separate analytical approaches. For the tabular data, we address class imbalance using oversampling techniques such as Adaptive Synthetic Sampling (ADASYN) and Synthetic Minority Over-Sampling Technique (SMOTE). Supervised learning algorithms are then used to predict fraudulent claims, with 
interpretability provided by Local Interpretable Model-agnostic Explanations (LIME). In parallel, claim-related images are analyzed using Convolutional Neural Networks (CNNs), with Gradient-weighted Class Activation Mapping (Grad-CAM) applied to generate heat maps that explain model decisions. To further enhance understanding, vision-language models like BLIP2 (via LAVIS) or CLIP are used to generate textual captions from the images.   
Our approach was evaluated using F1-score, precision-recall, and balanced accuracy. By analyzing tabular and image data independently, the system improves the accuracy of fraud detection while ensuring clarity through explainable AI techniques. This hybrid approach addresses the complexities of vehicle insurance fraud, offering a practical and effective solution for modern insurance operations. 
