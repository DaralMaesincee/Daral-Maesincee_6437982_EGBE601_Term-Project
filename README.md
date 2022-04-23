# Daral Maesincee_6437982_EGBE601_Term Project
Project Title: Segmentation of cancerous breast sonograms through the utilization of U-Net

Project Overview:

As one of the leading causes of death among women that is often misdiagnosed or underdiagnosed, breast cancer affected 7.8 million women worldwide, leading to approximately 685,000 deaths by the end of 2020 . Through the use of high frequency sound waves to produce real-time images or “sonograms” of various structures within the body, ultrasonography is a non-invasive and relatively harmless imaging technique utilized to further explore suspicious lesions detected by the preliminary physical examinations or mammography of the breast. Although it is an unsuitable screening technique as it is normally unable to produce clear images of the deeper regions within the breast and differentiate some of the early signs of cancer (e.g., microcalcifications), it is a preferred diagnostic method that is widely used by medical practitioners to identify different types of breast cancer. Since ultrasonography is one of a very few non-invasive diagnostic tools for a disease with such rapidly growing prevalence, it is beyond crucial to further advance its abilities to develop a highly accurate early detection tool to potentially lower the number of deaths from breast cancer in the future. Therefore, this study aims to utilize signal processing to segment various breast sonograms for improved prediction accuracy of the disease through the convolutional network architecture, U-Net. 

The data collected at baseline in 2018 used in this study was obtained from Kaggle, consisting of 780 breast ultrasound images of 600 female patients aged 25 – 75 years, with an average image size of 500*500 pixels. These images were readily grouped into three categories: normal, benign, and malignant. Most of the dataset was used for training (Train_Daral Maesincee_Term Project.ipynb) and the rest was used for testing (Test_Daral Maesincee_Term Project.ipynb). 

Train Accuracy: 91.82% (epoch = 50, loss = 24.29%)

Test Accuracy: 86.28%

Note: no additional requirements are needed to run the code.
