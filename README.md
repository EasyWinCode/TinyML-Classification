# TinyML-Classification
**TinyML Classification for Agriculture Objects with ESP32**

  **by Danila Donskoy, Valeria Gvindjiliya and Evgeniy Ivliev**
  
  Laboratory “Modeling and Development of Intelligent Agricultural Engineering Systems”, Don State Technical University, Rostov-on-Don 344000, Russia
  
  Article on MDPI: **https://www.mdpi.com/2673-6470/5/4/48**

  Using systems with machine learning technologies for process automation is a global trend in agriculture. However, implementing this technology comes with challenges, such as the need for a large amount of computing resources under conditions of limited energy consumption and the high cost of hardware for intelligent systems. This article presents the possibility of applying a modern ESP32 microcontroller platform in the agro-industrial sector to create intelligent devices based on the Internet of Things. CNN models are implemented based on the TensorFlow architecture in hardware and software solutions based on the ESP32 microcontroller from Espressif company to classify objects in crop fields. The purpose of this work is to create a hardware–software complex for local energy-efficient classification of images with support for IoT protocols. The results of this research allow for the automatic classification of field surfaces with the presence of “high attention” and optimal growth zones. This article shows that classification accuracy exceeding 87% can be achieved in small, energy-efficient systems, even for low-resolution images, depending on the CNN architecture and its quantization algorithm. The application of such technologies and methods of their optimization for energy-efficient devices, such as ESP32, will allow us to create an Intelligent Internet of Things network.

  As a result, the architecture used in practice was chosen and the algorithm operated at a resolution of 80 × 60 (figure 9), which ensured an **accuracy of 87%** with a maximum **classification time of up to 8 s**. Data collection and classification are implemented locally on the micro-controller (figure 13), which allows for mobile analysis of the surfaces of crop fields and the creation of data arrays on their condition. We can also plot a map showing the weediness and crop yields of fields. Implementing such a system can help to optimize the use of resources; for example, when treating fields with fertilizers and herbicides.


<img width="706" height="428" alt="image" src="https://github.com/user-attachments/assets/c27c0ba0-b0fd-4625-9273-87d4f16f9248" />

<img width="692" height="379" alt="image" src="https://github.com/user-attachments/assets/d63a89b3-2e24-4635-8d22-795c5f1c4300" />


 **Funding:**
 
 This work was carried out within the framework of the project “Mathematical modeling and algorithms for modeling plant growth based on an automated cartographic system” (FZNE2024-0006).

Contacts for questions: dand22@bk.ru
