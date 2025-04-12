---

```markdown
# 🎵 Assignment 3 – Music Recommendation System

## 📁 Folder Structure

```
Assignment_3_Manisha/
├── src/
│   ├── task1.py
│   ├── task2.py
│   ├── task3.py
│   ├── task4.py
│   ├── task5.py
│   └── task6.py
├── generate_listening_logs.py
├── generate_songs_metadata.py
├── listening_logs.csv
├── songs_metadata.csv
└── README.md
```

## 📌 Project Description

This project simulates a basic music recommendation pipeline. It involves the generation, preprocessing, and analysis of music listening data using PySpark. The system uses synthetic datasets for user listening logs and song metadata, and it progresses through multiple tasks to explore, transform, and extract insights.

---

## ⚙️ Setup Instructions

### ✅ Prerequisites

Make sure you have the following installed:

- Python 3.11+
- [Java JDK 8 or higher](https://adoptium.net/)
- pip packages:
  ```bash
  pip install pyspark pandas
  ```

---

### 🛠 Java Setup (Required for PySpark)

1. **Install Java JDK**: Download and install from [Adoptium](https://adoptium.net/) or Oracle.

2. **Set Environment Variable `JAVA_HOME`** (for Windows):
   - Open **Environment Variables**
   - Click **New** under *User variables*
     - Name: `JAVA_HOME`
     - Value: path to your JDK, e.g., `C:\Program Files\Java\jdk-21`
   - Edit `Path` → Add: `%JAVA_HOME%\bin`

3. **Verify**:
   ```bash
   java -version
   echo %JAVA_HOME%
   ```

---

## ▶️ How to Run

Run any task file from the terminal:

```bash
python src/task1.py
python src/task2.py
...
```

To regenerate the CSV datasets:

```bash
python generate_listening_logs.py
python generate_songs_metadata.py
```

---

## 📂 Dataset Details

- **songs_metadata.csv**: Contains metadata like song ID, artist, genre, and duration.
- **listening_logs.csv**: Contains user listening session data (e.g., user ID, song ID, timestamp).

---

## 📌 Task Breakdown

| Task File   | Description                                         |
|-------------|-----------------------------------------------------|
| `task1.py`  | Load and inspect metadata                          |
| `task2.py`  | Clean and process listening logs                   |
| `task3.py`  | Join listening logs with metadata                  |
| `task4.py`  | Analyze most played songs and artists              |
| `task5.py`  | Basic recommendation logic based on popularity     |
| `task6.py`  | Advanced analytics or bonus recommendation methods |

---


