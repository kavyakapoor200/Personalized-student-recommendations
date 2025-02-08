## 📽️ Project Demo

🔗 [Watch the video here](https://drive.google.com/file/d/1xyqakcNvdsZ7Ph_M-lz3gcoL3Zflj5na/view?usp=sharing)

---

# **Personalized Student Recommendation System**  

## **Overview**  
The **Personalized Student Recommendation System** is an AI-driven approach to analyzing students' quiz performance and providing targeted recommendations for improvement. This system evaluates quiz responses, identifies weak areas, and suggests strategic learning paths to enhance subject understanding.  

## **Features**  
- **Quiz Performance Analysis** – Computes student accuracy across multiple topics.  
- **Student Persona Identification** – Categorizes students based on strengths and weaknesses.  
- **Personalized Recommendations** – Provides tailored suggestions to improve subject proficiency.  
- **Performance Visualization** – Graphical insights into quiz performance trends.  

Here’s a **detailed approach description** you can include in your README:  

---

### **Approach Description**  

Our **Personalized Student Recommendation System** is designed to analyze student quiz performance and provide customized insights for improvement. The project follows a structured workflow:  

#### **1. Data Processing**  
- Extracts relevant details from **Current Quiz Data** (latest quiz attempt) and **Historical Quiz Data** (previous attempts).  
- Cleans and preprocesses the dataset to ensure consistency.  
- Maps quiz responses to corresponding **topics, difficulty levels, and accuracy rates**.  

#### **2. Performance Analysis**  
- Computes **overall accuracy** across all quizzes.  
- Breaks down performance by **topic**, identifying strengths and weaknesses.  
- Tracks **trends in accuracy**, detecting improvements or declines in specific areas.  

#### **3. Student Persona Identification**  
- Categorizes the student based on their performance trends.  
- Assigns a **persona label** (e.g., "Emerging Talent," "Potential Learner") to provide meaningful insights.  
- Highlights specific **strengths and areas needing improvement** based on historical accuracy.  

#### **4. Personalized Recommendations**  
- Generates tailored study recommendations:  
  - Topics requiring **extra focus**.  
  - Areas where performance is **declining**.  
  - Strong topics where consistency should be maintained.  
  - Suggested **difficulty levels and question types** for targeted practice.  

## **Project Structure**  
```
Personalized-Student-Recommendations
│-- Kavya_Testline.ipynb   # Jupyter Notebook containing the implementation  
│-- README.md              # Project documentation  
│-- available_ids.png      # Screenshot displaying available student IDs  
│-- bar_psr.png           # Bar chart illustrating topic-wise performance
|-- feteched_dataset_overview.ipynb  #dataset_columns_overview  
│-- output_psr.png         # Snapshot of quiz analysis results  
```

## **Installation & Usage**  
### **Clone the Repository**  
```bash
git clone https://github.com/kavyakapoor200/Personalized-student-recommendations.git
cd Personalized-student-recommendations
```

### **Run the Notebook**  
1. Open Google Colab or Jupyter Notebook.  
2. Load and execute the `Kavya_Testline.ipynb` file.  
3. Upload quiz data if required.  
4. Analyze student performance and view recommendations.  

## **Insights & Visualizations**  
- **Overall Accuracy**: Displays the student's quiz performance percentage.  
- **Topic-Wise Performance**: Identifies strengths and areas that need improvement.  
- **Personalized Recommendations**: Suggests targeted study plans based on quiz results.  
- **Graphical Representations**:  
  - `bar_psr.png` – Bar chart illustrating performance across topics.  
  - `output_psr.png` – Final output summarizing student analytics.  

## **Future Enhancements**  
- **NEET Rank Prediction** – Machine Learning model to estimate NEET ranking based on historical performance.  
- **Enhanced Data Insights** – Advanced analytics with deeper topic-wise segmentation.  
- **Interactive Dashboards** – Web-based interface for real-time progress tracking.  

## **Contributing**  
Contributions are welcome! If you would like to improve this project:  
1. **Fork** the repository.  
2. **Create a new branch** for your feature.  
3. **Submit a pull request** with detailed explanations of your changes.  

## **Contact & Support**  
For any queries or issues, feel free to reach out via GitHub Issues.  

---
