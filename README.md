# 📊 Data Science & Machine Learning Notebooks

รวมไฟล์ Jupyter Notebook สำหรับฝึกฝนพื้นฐาน **Python, Data Science และ Machine Learning** ตั้งแต่พื้นฐานภาษาไปจนถึงการสร้างโมเดลทำนายและจัดกลุ่มข้อมูลด้วย scikit-learn

---

## 📓 เนื้อหาในแต่ละไฟล์ (Notebooks)

| ไฟล์ | เนื้อหา |
|---|---|
| `Data__Science1.ipynb` | พื้นฐานภาษา Python: ตัวแปร, ชนิดข้อมูล (type casting), string operations |
| `Data_Science2.ipynb` | การทำงานกับวันที่-เวลา (`datetime`), การเขียนฟังก์ชัน (เช่น คำนวณพื้นที่วงกลม/สี่เหลี่ยม, แปลงหน่วยเงิน) |
| `LinearRegression.ipynb` | สร้างโมเดล **Linear Regression** ทำนายผลจากข้อมูล `study.csv` (ชั่วโมงเรียน → คะแนนสอบ) และ `insurance.csv` (ปัจจัยผู้เอาประกัน → ค่าใช้จ่ายประกันสุขภาพ) |
| `knn_iris.ipynb` | สร้างโมเดลจำแนกประเภท **K-Nearest Neighbors (KNN)** บนชุดข้อมูล Iris พร้อม normalization (`StandardScaler`) และประเมินผลด้วย accuracy/classification report |
| `K_mean_iris.ipynb` | จัดกลุ่มข้อมูลแบบ **K-Means Clustering** บนชุดข้อมูล Iris พร้อมลดมิติด้วย **PCA** เพื่อพล็อตผลลัพธ์เป็น 2 มิติ |

## 🗂️ ชุดข้อมูล (Datasets)

* `study.csv` — ความสัมพันธ์ระหว่างชั่วโมงเรียน (Hours) กับคะแนนสอบ (Scores)
* `insurance.csv` — ข้อมูลผู้เอาประกันสุขภาพ (อายุ, เพศ, BMI, จำนวนบุตร, การสูบบุหรี่, ภูมิภาค) กับค่าใช้จ่ายที่เรียกเก็บ (charges)
* Iris dataset — โหลดตรงจาก `sklearn.datasets` (ใช้ทั้งใน `knn_iris.ipynb` และ `K_mean_iris.ipynb`)

---

## 🛠️ เทคโนโลยีที่เลือกใช้ (Tech Stack)

* **Python** (รันผ่าน Jupyter Notebook)
* **[pandas](https://pandas.pydata.org/) / [NumPy](https://numpy.org/):** จัดการและประมวลผลข้อมูล
* **[scikit-learn](https://scikit-learn.org/):** สร้างโมเดล Linear Regression, KNN, K-Means และเครื่องมือช่วย เช่น `train_test_split`, `StandardScaler`, `PCA`
* **[Matplotlib](https://matplotlib.org/):** พล็อตกราฟและผลลัพธ์การจัดกลุ่มข้อมูล

---

## 🚀 วิธีใช้งาน (Getting Started)

```bash
# ติดตั้งไลบรารีที่จำเป็น
pip install pandas numpy scikit-learn matplotlib jupyter

# เปิดใช้งาน Jupyter Notebook
jupyter notebook
```

จากนั้นเปิดไฟล์ `.ipynb` ที่ต้องการแล้วรันทีละเซลล์ (Run All หรือ Shift+Enter ไล่ไปทีละเซลล์)

---

## 👥 ผู้พัฒนา (Developer)

* **Nuttaphat** ([@flame123-np](https://github.com/flame123-np))

*(หมายเหตุ: โน้ตบุ๊กชุดนี้จัดทำในภาคการศึกษา 2567 กลุ่มเรียน 820 — สังเกตได้จากชื่อไฟล์ `README.md` เดิมในรีโปที่ระบุ `242-2567-820`)*
