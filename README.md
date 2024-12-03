# NutriDetect: Food Detection and Nutritional Insights 
<div>
  <img src="/Images/NutriDetect.png" alt="Nutridetect" />
</div>

## 🍴 Overview  
NutriDetect is an advanced platform designed to detect and classify food items from diverse cuisines. Leveraging cutting-edge machine learning models, it provides real-time object detection, classification, and nutritional insights, aiming to redefine food recognition technology.

## 🔬 Key Features  
- **Diverse Dataset**: Includes images of food items from popular cuisines and restaurant chains. Expanding to cover global culinary diversity.  
- **State-of-the-Art Models**: Experimenting with YOLO to identify the optimal model for accuracy and efficiency.  
- **User-Centric Design**: Designed for easy integration with mobile and web applications for real-time use.  
- **Nutrition Insights**: Offers detailed nutritional content for detected food items.  

## 👥 Research Team  
- **Thirupathi kadari** - Project Lead
- **Sayed Raheel Hussain** - Research Contributor 
- **Tushar Sinha** - Visionary and Advisor  
  

## 🛠 Technical Architecture  

### Model Details  
- Models: YOLOv8m, Yolo11m  
- Framework: PyTorch 
- Dataset: UECFOOD dataset with labeled bounding boxes for over 250+ food categories 
- Deployment: Cloud-optimized and mobile-compatible  

### Application Features  
1. Multi-class object detection and classification  
2. Bounding box generation with confidence scores  
3. Real-time prediction capability  
4. API-ready for easy integration with other platforms  


## 📊 Performance Metrics  

| Model    | Image Size | Epochs | mAP@0.5 | mAP@0.5:0.95 |
|----------|------------|--------|---------|--------------|
| YOLOv8m  | 640x640    | 26     | 0.652   | 0.507        |
| YOLO11m  | 640x640    | 48     | 0.758   | 0.601        | 

## 🍽 Dataset
You can find the dataset in the following locations:
- [Google Drive](https://drive.google.com/drive/folders/14rJclN97hZqe6bmGkTjnvPaDBBIF4v5w)
  

## 🎯 Goals  
1. Train and fine-tune the best-performing model on a large, diverse food dataset.  
2. Integrate nutritional insights for detected food items.  
3. Create a user-friendly application for real-world use.  

## 📱 Application Screenshots  

### Home Page  
<div>
  <img src="./Images/Home_page.png" alt="Home Page" >
</div>

### Description Page  
<div>
  <img src="./Images/Description_page.png" alt="Description Page" >
</div>

### Try Models Page  
<div>
  <img src="./Images/Try_models.png" alt="Try Models Page" >
</div>


### 🍔 Sample Results 


<div>
  <img src="./Images/Prediction_1.png" alt="Single Food Detection" >
</div>

<div>
  <img src="./Images/Prediction_2.png" alt="Multiple Food Detection" >
</div>

### Nutritional Insights  
**Detailed Nutritional Content Example:**  
<div>
  <img src="./Images/Nutritional_content.png" alt="Nutritional Content">
</div>


## 🔗 Next Steps  
NutriDetect aims to scale into a complete ecosystem with the following features:  
1. Calorie tracking for dietary management  
2. Recipe suggestions based on detected food items  
3. Integration with health apps and devices 

## 📄 Citations  


## 🤝 Contributing  
We welcome contributions from the research and developer community. Please read our contributing guidelines before submitting pull requests.

## 📫 Contact  
For collaboration inquiries, please contact:  
- **Thirupathi Kadari**
- **Syed Raheel hussain**
- **Tushar Sinha**  

## 📃 License  
[License information to be added]
