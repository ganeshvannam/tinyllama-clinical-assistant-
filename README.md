# AI-Driven Personalized Health Assistant

## 🧠 Project Overview
This project is a real-time, voice-enabled clinical assistant designed to deliver personalized health responses. It listens to a user’s question, understands their health context using structured patient data, and responds in natural language using a lightweight language model (TinyLLaMA).

The assistant mimics a conversation with a human healthcare provider by combining six simulated patient datasets (EHR-like) with voice recognition and AI-generated replies. It works entirely on standard machines without requiring cloud services or GPU acceleration, making it highly accessible.

Our goal was to create an intelligent assistant that feels interactive, speaks clearly, and understands individual health history — all while staying fast, lightweight, and user-friendly.

## 👥 Team Members
- Ganesh Vannam  
- Yaswanth Ganapathi

## 🎯 Project Goal
To design a lightweight, intelligent health assistant that:
- Listens to spoken medical questions
- Understands individual patient health data
- Speaks back in the user’s preferred language
- Runs on standard laptops with low memory usage

## ⚙️ Technologies Used
- **TinyLLaMA-1.1B** (Hugging Face): LLM used for generating responses  
- **Google Speech-to-Text API**: For converting voice input to text  
- **gTTS**: To speak the response back to the user  
- **Python + Transformers Library**: Used to build the assistant logic

## 📁 Files in This Repository
- `Clinical Assistant.ipynb` – Final code notebook  
- `Final_Presentaion.pdf` – Slides used for the project presentation  
- `Proje_ Demo.MP4` –Demo of our project
- `Datasets.zip` – Patient health data used to personalize responses  
- `Progress Report 1.pdf` – Initial proposal and planning  
- `Progress Report 2.pdf` – Mid-project update with implementation steps

## 📊 Dataset Description
We created 6 datasets to simulate real patient records:
- Patient Profiles  
- Allergies and Diet  
- Mental Health and Mood  
- Clinical Encounters  
- Lab Results  
- PG Health Data (vitals, steps, etc.)

These datasets helped the assistant provide personalized answers.

## 📹 Presentation Video
🎥 YouTube link: https://www.youtube.com/channel/UCyAsWmyMVqXOSt82ZWxXIIA

## 🚀 How to Run
1. Install Python libraries:  
   `pip install transformers gtts speechrecognition langdetect`
2. Run the notebook in Google Colab or Jupyter  
3. Ask a health-related question out loud  
4. The assistant will respond with a personalized voice answer

## 📚 References
- Hugging Face. (2024). [TinyLLaMA-1.1B-Chat-v1.0](https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0)  
- Wang et al. (2018). Clinical Information Extraction. *Journal of Biomedical Informatics*  
- Singhal et al. (2023). MedPaLM. *arXiv:2305.09617*  


---

© 2024 Ganesh Vannam & Yaswanth Ganapathi – Michigan Technological University
