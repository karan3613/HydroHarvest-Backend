# 💧 HydroHarvest Backend

### 🌱 AI + IoT Powered Water & Crop Management System

HydroHarvest is the backend service powering an autonomous **smart farming and water-management app**.  
It combines **Machine Learning**, **IoT insights**, and **Retrieval-Augmented Generation (RAG)** to help farmers monitor their environment, detect crop diseases, and learn from agricultural texts in their preferred language.

## 🔗 Repositories & Links

- 📱 **Frontend App (Jetpack Compose):** [View Repository](https://github.com/karan3613/HydroHarvest)  
- 💼 **LinkedIn Project Post:** [Read Story & Demo](https://www.linkedin.com/posts/karan-chouhan-57a337283_hackathon-agritech-iot-activity-7353893473642569729-bLAL?utm_source=share&utm_medium=member_desktop&rcm=ACoAAETtOW4BGUyz-H1DfZENmLTxZMycY_DLoNE)


## 🚀 Features

### 🔍 Retrieval-Augmented Insights
- Uses **RAG (Retrieval-Augmented Generation)** built with **LangChain** and **FAISS**  
- Indexes agricultural books, PDFs, and research papers for instant retrieval  
- Converts complex material into simple, actionable answers for farmers  
- Multilingual support for translation and localization

### 🌾 Crop Disease Detection
- CNN-based image classification model trained to detect crop diseases  
- Farmers can upload plant images for instant disease prediction  
- Returns confidence score and preventive recommendations

### 💧 Water & Soil Health Prediction
- **SVM model** trained on 3,000 + observations to evaluate water quality (pH, conductivity, turbidity, etc.)  
- Predicts optimal irrigation strategies and filtration needs  
- Helps build a circular filtration system using farm by-products

### 🧠 Language Intelligence
- LangChain + LLM integration refines technical results into natural, context-aware answers  
- Breaks language barriers so farmers can access guidance in their native language

### 🛰️ IoT Integration Ready
- Designed to integrate seamlessly with field IoT sensors  
- Streams soil moisture, temperature, and pH data directly into AI models



## 🧩 Tech Stack

| Layer | Technologies |
|-------|---------------|
| **Backend Framework** | FastAPI, Python |
| **AI / ML Models** | TensorFlow (CNN), scikit-learn (SVM) |
| **Knowledge Retrieval** | LangChain + FAISS + Sentence-Transformers |
| **Vector Embeddings** | `all-MiniLM-L6-v2` |
| **Deployment** | Docker + NGINX |
| **Data** | 3,000 + observations (water/pH dataset) + curated agriculture texts |


## 🔬 Training Overview

| Model        | Algorithm                      | Data Size          | Purpose                  |
|---------------|--------------------------------|---------------------|---------------------------|
| **CNN**       | Convolutional Neural Network   | ~10k images         | Crop disease detection    |
| **SVM**       | Support Vector Machine         | 3,000 observations  | Water/pH classification   |
| **RAG + LLM** | LangChain + FAISS              | 50+ agriculture docs | Knowledge retrieval       |

