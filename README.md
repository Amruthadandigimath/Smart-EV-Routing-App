# LIDAR Obstacle Detection App

**Team - Mind_Mesh**  
**Developers**: Amrutha D, Vishnu V  
**Institution**: REVA University, Bangalore

---

## 🔴 Live Demo  
[Click here to try the app](https://lidar-obstacle-detection-app.streamlit.app/)

## 🧠 GitHub Repository  
[https://github.com/gv-2309/Lidar-obstacle-detection-App](https://github.com/gv-2309/Lidar-obstacle-detection-App)

---

## 🚩 Problem Statement  
**[Robotics] Problem-1.1: Obstacle Detection using LIDAR Data of a Robot**

---


## 💡 Features

- 📂 Upload your own LIDAR CSV file or choose from built-in test cases
- 🛑 Detects obstacles within a **10-meter radius** from origin (0, 0, 0)
- 🧭 Categorizes detected points based on distance:
  - 🔴 **High Danger**: < 3 meters
  - 🟠 **Medium Danger**: 3–6 meters
  - 🟢 **Low Danger**: 6–10 meters
- 🧠 Clusters nearby obstacle points using **DBSCAN**
- 📊 Displays an interactive 2D scatter plot with all points and danger zones
- 💻 Simple, interactive interface powered by Streamlit

---

## 📦 Requirements

Install required Python libraries:

```bash
pip install -r requirements.txt
````

---

## 💻 How to Run the App Locally (VS Code)

### 1. Clone the Repository

```bash
git clone https://github.com/gv-2309/Lidar-obstacle-detection-App
cd Lidar-obstacle-detection-App
```

### 2. Create and Activate Virtual Environment (Recommended)

```bash
# Create
python -m venv venv

# Activate (Windows)
venv\Scripts\activate

# Activate (Mac/Linux)
source venv/bin/activate
```

### 3. Install Python Dependencies

```bash
pip install -r requirements.txt
```

### 4. (Linux Only) Install System Dependency

```bash
sudo apt-get install libgl1-mesa-glx
```

---

## 📁 Folder Structure

Make sure your project files are organized as below:

```
lidar-obstacle-detection-app/
├── main.py
├── requirements.txt
├── packages.txt
├── lidar_test_files/
│   ├── test_case_1.csv
│   └── test_case_2.csv
```

---

## ▶️ Run the App

```bash
streamlit run main.py
```

---

## 🌐 Open in Browser

Visit: [http://localhost:8501](http://localhost:8501)

---

## 📥 Sample Input Format

The CSV file should contain 3D point cloud data **(no headers)** with the format:

```
X, Y, Z
10, 0, 0
1, 1, 0
...
```

---

## 🎥 Demo Video

📺 [Watch the demo](https://tinyurl.com/hackotsav-2k25)

---

## 📞 Contact

For queries or collaboration, reach out:

* Vishnu V — [vishnuv2309@gmail.com](mailto:vishnuv2309@gmail.com)
* Amrutha D — [amruthadandigimath@gmail.com](mailto:amruthadandigimath@gmail.com)

```


