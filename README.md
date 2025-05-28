# NYCU-Computer-Vision-2025-HW4
Student-ID: 110550085  
Name: 房天越  
## Introduction
In this homework, we aim to implement Image Restoration for two kinds of degrading, Snow and Rain.  
We can apply PromptIR to improve the performance.  
Our core idea is to integrate noise-type prompts (labels) into a U-Net backbone using Feature-wise Linear Modulation (FiLM).  
## How to install
1. Create a virtual environment using conda, naming cvhw4 for example.  
   ```conda create -n cvhw4 python=3.10 -y```  
2. Activate the environment.
   ```conda activate cvhw4 ```  
3. Install the requirements.txt  
   ```pip install -r requirements.txt```  
4. Train the model with only one model or two models separately  
   ```python train_promptir.py``` or ```python train_weather.py```  
5. Inference and get the images  
   ```python test_promptir.py``` or ```python test_weather.py```  
6. Transform the images to pred.npz
   ```python example_img2npz.py```
## Performance Snapshot  
<img width="1161" alt="截圖 2025-05-28 晚上9 47 29" src="https://github.com/user-attachments/assets/6b36091e-8ec7-4a5b-8b04-8e1ef25d9db7" />  
