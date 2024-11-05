# แอปจำแนกประเภทเห็ด

## ภาพรวม
แอปนี้ช่วยในการจำแนกเห็ดว่าเป็นกินได้หรือพิษ โดยใช้โมเดล Machine Learning บนชุดข้อมูล UCI Mushroom

## วัตถุประสงค์
ให้ผู้ใช้ป้อนลักษณะเห็ดและรับการทำนายเกี่ยวกับการกินได้

## โมเดลที่ใช้
- SVM
- Logistic Regression
- Random Forest

## ชุดข้อมูล
ใช้ **UCI Mushroom dataset** ที่ประกอบด้วยลักษณะของเห็ดและสถานะการกินได้

## การติดตั้ง
ติดตั้งไลบรารีที่จำเป็น:

```bash
pip install streamlit scikit-learn pandas
