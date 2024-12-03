# Nutridetect: Comprehensive Food Detection and Classification Platform  
<div>
  <img src="/Images/NutriDetect.png" alt="Nutridetect" />
</div>

## 🍴 Overview  
FoodVision is an advanced platform designed to detect and classify food items from diverse cuisines, including American, Indian, Chinese, and Mexican. Leveraging cutting-edge machine learning models, it provides real-time object detection, classification, and nutritional insights, aiming to redefine food recognition technology.

## 🔬 Key Features  
- **Diverse Dataset**: Includes images of food items from popular cuisines and restaurant chains. Expanding to cover global culinary diversity.  
- **State-of-the-Art Models**: Experimenting with YOLO and Faster R-CNN to identify the optimal model for accuracy and efficiency.  
- **User-Centric Design**: Designed for easy integration with mobile and web applications for real-time use.  
- **Nutrition Insights**: Offers detailed nutritional content for detected food items.  

## 👥 Research Team  
- **Thirupathi kadari** - Project Lead
- **Sayed Raheel Hussain** - Research Contributor 
- **Tushar Sinha** - Visionary and Advisor  
  

## 🛠 Technical Architecture  

### Model Details  
- Models: YOLOv8, Faster R-CNN (under evaluation)  
- Framework: PyTorch 
- Dataset: UECFOOD dataset with labeled bounding boxes for over 100+ food categories 
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

## 🍽 Dataset Creation  
FoodVision's dataset is built using:  
1. **Images from Restaurant Chains**: Scraped images from websites and Google reviews.  
2. **Custom Labeling**: Bounding boxes and food labels annotated manually.  
3. **Dataset Augmentation**: Enhanced data using advanced augmentation techniques for robustness.  

## 🎯 Goals  
1. Train and fine-tune the best-performing model on a large, diverse food dataset.  
2. Integrate nutritional insights for detected food items.  
3. Create a user-friendly application for real-world use.  

## 📱 Application Screenshots  
<div>
  <img src="/images/App1.png" alt="FoodVisionApp" />
</div>

<div>
  <img src="/images/App2.png" alt="FoodVisionApp2" />
</div>

## 🔗 Next Steps  
FoodVision aims to scale into a complete ecosystem with the following features:  
1. Calorie tracking for dietary management  
2. Recipe suggestions based on detected food items  
3. Integration with health apps and devices  
4. Partnerships with restaurants for digital menu scanning  

## 📄 Citations  
If you use this work in your research, please cite:  
[Your paper or research citation here]

## 🤝 Contributing  
We welcome contributions from the research and developer community. Please read our contributing guidelines before submitting pull requests.

## 📫 Contact  
For collaboration inquiries, please contact:  
- **Your Name**  
- **Tushar Sinha**  

## 📃 License  
[License information to be added]
