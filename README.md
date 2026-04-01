# 🧘 Yoga Pose Analysis Project

## 📌 Introduction
Yoga is for everyone, and it helps improve overall health and well-being. In this project, I analyzed various yoga poses by creating a custom dataset that captures multiple attributes such as:

- Body part targeted  
- Muscle group involved  
- Benefits  
- Health conditions addressed  
- Difficulty level  
- Type of yoga  

The dataset includes poses like *Tadasana*, *Balasana*, and others. The goal is to analyze how yoga combinations relate to body parts, determine whether classes are required, and visually map these relationships onto a human body.

---

## ⚠️ Assumptions

This analysis is based on the following assumptions:

- The dataset is created using publicly available information and may have limitations.
- No segmentation based on ethnicity, gender, or race is included.
- The analysis focuses on **pose types**, not the complete philosophy of yoga.
- Health metrics such as BMI and detailed medical conditions are not considered.

---

## 📊 Dataset

- Custom dataset of **25 yoga poses**
- Key columns:
  - Pose
  - Body_Part
  - Muscle_Group
  - Benefit
  - Health_Condition
  - Difficulty
  - Type

---

## ❓ Research Questions

1. Which body parts get the most benefits?  
2. Which diseases are most targeted?  
3. Are yoga classes required for every type and pose?  
4. Is there a correlation between body parts and yoga types, and does it help reduce pain?  
5. What are the best yoga combinations for standing, sitting, and back pain?  
6. Can we predict yoga poses based on diseases?  
7. How can we map yoga poses on a human body?

---

## 🛠️ Tools Used

- Python  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## 🔍 Findings

### 1. Body Parts with Maximum Benefits
- The **spine** receives the most benefits.
- Followed by:
  - Full body  
  - Legs  
- Indicates strong focus on posture and mobility.

---

### 2. Diseases Most Targeted
- **Back Pain** (most frequent)
- Followed by:
  - Obesity  
  - Anxiety  
  - Fatigue  
  - Stress  

👉 Insight: Yoga is highly effective for lifestyle and musculoskeletal issues.

---

### 3. Are Yoga Classes Required?

- Beginner: 11 poses → No training required  
- Intermediate: 11 poses → Optional guidance  
- Advanced: 3 poses → Training required  

👉 Conclusion:
- Most poses are self-learnable  
- Intermediate poses benefit from guidance  
- Advanced poses require supervision  

---

### 4. Correlation: Body Part vs Yoga Type

- Backbend → Spine & Chest  
- Balance → Legs  
- Meditation → Mind  
- Standing → Legs  

#### Pain Analysis:
- Majority of pain-related poses target the **spine**
- Movement types involved:
  - Stretch → Relief  
  - Twist → Mobility  
  - Backbend → Strength  

---

### 5. Best Yoga Combinations

#### 🧍 Standing Improvement
- Tadasana (Mountain Pose)  
- Trikonasana (Triangle Pose)  
- Virabhadrasana I (Warrior I)  
- Virabhadrasana II (Warrior II)  

#### 🪑 Sitting Improvement
- Vajrasana (Thunderbolt Pose)  
- Sukhasana (Easy Pose)  
- Padmasana (Lotus Pose)  

#### 🦴 Back Pain Relief
- Bhujangasana (Cobra Pose)  
- Setu Bandhasana (Bridge Pose)  
- Dhanurasana (Bow Pose)  
- Ardha Matsyendrasana (Half Spinal Twist)  
- Chakrasana (Wheel Pose)  

---

### 6. Yoga Prediction Model

- Built using:
  - **CountVectorizer**
  - **DecisionTreeClassifier**

#### Function:
def predict_yoga(disease):
    ## 🤖 Yoga Prediction System

**Input:** Disease  
**Output:** Recommended Yoga Pose  

This system uses a machine learning approach to suggest yoga poses based on specific health conditions, enabling personalized recommendations.

---

## 🗺️ Human Body Mapping

### 🔧 Tools Used
- `matplotlib.image`  
- `matplotlib.patches`  

### 📊 Visualization Features
- Yoga poses mapped onto different body regions  
- Heat/intensity representation based on number of poses  

### 🎯 Insights from Visualization
- Identifies dominant body areas targeted by yoga  
- Highlights regions with maximum therapeutic impact  
- Helps understand pose-to-body relationships visually  

---

## 🧠 Conclusion

Yoga significantly improves physical health, especially:

- Spine  
- Posture  
- Mobility  

### 🔍 Key Insights
- Most yoga poses are **beginner-friendly**  
- Intermediate poses require **guidance**  
- Advanced poses need **professional supervision**  

### 🚀 Project Contributions
- Data-driven yoga recommendations  
- Visual mapping of body impact  
- Predictive modeling for health-based yoga suggestions  

---

## Author
Sibankar Saha
