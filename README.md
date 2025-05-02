# 🎲 **Automatic Attendance System**

> This project was created as part of my CVDL Innovative Assignment in the 6th semester.

---

## 📜 Project Description
> This project implements a **Automatic Attendance System** using FaceNet and MTCNN to solve the problems of Traditional methods of roll call that are time-consuming and prone to human error.

---

---

## ❓ Problem Statement
> Traditional methods of attedance system can be prone to human error like missed names, incorrect entries or miscounts. Also, traditional systems are vulnerable to proxy attendance. Maintaining paper-based records requires physical storage also. This project eliminates this issue by providing AI-based solution for attedance system.

---

## 🔩 Components Used
✅ **FaceNet** – Generates face embeddings. 
✅ **MTCNN** – for Face Recognition
✅ **Augmentor** – for Data Augmentation. 

---

## 📥 Why this Solution
**MTCNN vs YOLO :**
> MTCNN outperforms YOLO in detecting multiple faces in group photos, handling occlusions and overlapping faces better. YOLO struggles with crowded scenes, often missing faces or detecting them incorrectly, especially when faces are close together. MTCNN is more reliable in varied environments (e.g., classrooms or events) where faces may not be fully visible or evenly lit.

**FaceNet for Embedding Generation :**
> FaceNet creates high-quality embeddings that remain consistent even under lighting and angle variations, making it ideal for attendance systems.

---

## ⚙️ Solution 

1️⃣ **Press the button** – Triggers the rolling process.  
2️⃣ **Random number generation** – Produces a number between **1 and 6**.  
3️⃣ **Logic circuit processes the output** – Ensures valid results.  
4️⃣ **LEDs light up** – Displays the corresponding dice pattern.  
5️⃣ **7-Segment display updates** – Shows the rolled number clearly.  

---

## 🛠️ Circuit Design
🔹 The circuit integrates the following components:  
✔️ **Push Button** – Initiates the rolling.  
✔️ **Random Number Generator** – Produces unpredictable values.  
✔️ **Logic Gates** – Ensures correct output range (1-6).  
✔️ **7-Segment Display** – Shows the dice value numerically.  

### 🖼️ Circuit Diagram:
![Circuit Diagram](circuit_diagram.png)

---

## 📊 Truth Table
![Truth Table](truth_table.png)

---

## 💡 LED Logic Expressions
Each LED is controlled using **Boolean expressions** derived from **Karnaugh Maps (K-maps)**. The K-map technique helps simplify the logic equations, ensuring minimal logic gate usage while maintaining accuracy in representing dice patterns.

---

## 🎮 Applications
✅ **Board Games** – Use as an electronic dice replacement.  
✅ **Education** – Demonstrates logic gate applications.  
✅ **Random Number Generation** – Ideal for other electronics projects requiring randomness.  

---

## 📂 Repository Structure
```bash
📁 Digital-Dice/
 ┣ 📜 Digital Dice.circ
 ┣ 📜 README.md
 ┣ 📜 Report.pdf
 ┣ 📜 circuit_diagram.png
 ┣ 📜 truth_table.png

```

---

## 📞 Contact
🔗 [LinkedIn](https://www.linkedin.com/in/akshat-jingar/)  
