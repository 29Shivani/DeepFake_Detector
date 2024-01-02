# DeepFake_Detector

# Introduction
In our ever-evolving digital landscape, the rise of deepfake technology has raised significant concerns surrounding media authenticity. Deepfake, generated through artificial intelligence, blur the line between real and manipulated content, posing substantial threats to society. To address this pressing issue, we embark on the creation of a Deepfake Detection and Reporting System,PyTorch, MTCNN, and InceptionResnetV1 for Deepfake detection. Beyond identification, our system incorporates a pivotal reporting mechanism, enabling users to report detected fake content to a government portal, such as the National Cyber Crime Reporting Portal.

# Problem Statement
The proliferation of deepfake technology has led to a growing threat of manipulated multimedia content that can deceive, misinform, and potentially harm individuals and society at large. The challenge is to develop an effective and accessible system that can reliably detect fake content and provide a mechanism for reporting such content to relevant authorities, addressing the pressing need for safeguarding the integrity of digital media.
![image](https://github.com/29Shivani/DeepFake_Detector/assets/74962213/53f0e268-114d-4680-a397-7f3454be3214)

![image](https://github.com/29Shivani/DeepFake_Detector/assets/74962213/dd23c1fa-d494-4a17-b3ab-66c9a2757b9c)

# Solution
Solution is to create a Deepfake Detection and Reporting System that leverages advanced machine learning models and PyTorch to accurately identify deepfake content. Additionally, we will integrate a reporting mechanism that allows users to report  directly to a government portal, such as the National Cyber Crime Reporting Portal. This holistic approach not only enables informed decision-making regarding media authenticity but also facilitates swift actions by authorities to mitigate the spread of fake content, thereby preserving trust in digital media.

# Application Domain
**Social Media Platforms:**
Social media platforms can use this technology to automatically identify and flag deepfake images to prevent the spread of misinformation and protect users from potentially harmful content.

**News and Journalism:**
News organizations can integrate deepfake detection to verify the authenticity of images used in news articles and reports, ensuring the accuracy and credibility of their content.

**E-commerce and Online Marketplaces:**
E-commerce websites can employ deepfake detection to verify product images, ensuring that sellers provide genuine representations of their products and maintaining trust among online shoppers.

**Cybersecurity and Fraud Prevention:**
In the domain of cybersecurity, deepfake detection can be utilized to identify manipulated images in security surveillance systems, preventing unauthorized access and fraudulent activities.

**Human Resources and Recruitment:**
HR departments and recruitment platforms can use deepfake detection to validate the authenticity of candidate profile pictures and video interviews, ensuring a more secure and reliable hiring process.

# Software Requirements
**Python:** The code is written in Python, so you need a Python environment to run it.

**PyTorch:** This code uses PyTorch for deep learning. We  should have PyTorch installed, and it's recommended to have a GPU-enabled version.

**Gradio:** Gradio is a Python library for creating simple web interfaces for machine learning models. We need to install Gradio to run this code. You can install it using pip install gradio.

**Facenet_pytorch:** This library is used for face detection. Install it using pip install facenet-pytorch.

**OpenCV (cv2):** OpenCV is used for image processing and visualization. You need to have OpenCV installed. Install it with pip install opencv-python.

**Pillow (PIL):** PIL is used for working with images. Install it with pip install pillow.

# Dataset
**Faceforensics**
 - Video dataset
**Fake Catcher**
 - Dataset of synthetic images
**Kaggle**
 - Dataset augmented by meta

# Methodology
****Extraction ********
 - Face extraction from the image 
**Training**
 - Training the neural network 
 - Convolutional Neural network
**Conversion**
 - Masking using grad cam

# RESULT
![image](https://github.com/29Shivani/DeepFake_Detector/assets/74962213/5d42db78-fe5b-4015-aeec-f423e4072945)

![image](https://github.com/29Shivani/DeepFake_Detector/assets/74962213/80a35b59-ec5a-40f6-8a39-cdcc038767ba)

![image](https://github.com/29Shivani/DeepFake_Detector/assets/74962213/65955938-de77-4ef7-ad44-c76bdb8f5b76)

![image](https://github.com/29Shivani/DeepFake_Detector/assets/74962213/8da80113-40f0-4fee-b6ee-dc3483e42ff7)

# Demonstration of the Project

https://github.com/29Shivani/DeepFake_Detector/assets/74962213/00a62c9b-d005-43b2-a90a-a737068b2a75




