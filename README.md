# 🌯 Chipotle Order Analysis using Hadoop

<p align="center">
  <b>Big Data Fundamentals Project</b><br>
  <i>Implemented using Hadoop Ecosystem (HDFS, MapReduce, Hive)</i>
</p>

---

## 📌 Project Overview

This project demonstrates a complete Big Data processing pipeline to analyze transactional food order data using the Hadoop ecosystem.

With the increasing use of online food ordering systems, massive volumes of customer transaction data are generated daily. Traditional systems struggle to handle this efficiently.

This project extracts insights such as:

- Most popular food items  
- Total revenue generated  
- Customer ordering patterns  

---

## 🎯 Objectives

- To store large datasets using HDFS  
- To process data using MapReduce (Python)  
- To perform analytical queries using Hive  
- To understand distributed data processing  
- To generate business insights  

---

## 🏗️ Architecture
Raw CSV Dataset
↓
HDFS
↓
MapReduce
↓
Processed Output
↓
Hive
↓
Insights



---

## ⚙️ Technologies & Tools Used

- HDFS (Storage Layer)  
- MapReduce (Data Processing)  
- Hive (Data Analysis)  
- Python  
- Linux / Hadoop Environment  
- ChatGPT (Generative AI Assistance)  

---

## 📊 Dataset Information

The dataset contains transactional records of Chipotle orders.

### 📌 Key Attributes:

- order_id – Unique order identifier  
- item_name – Name of the food item  
- quantity – Number of items ordered  
- item_price – Price of each item  
- choice_description – Customizations (if any)  

---

## 🔄 Workflow Explanation

- Dataset is stored in HDFS for distributed storage  
- MapReduce processes the data to compute total sales and item frequency  
- Processed data is stored back in HDFS  
- Hive is used to run queries and analyze results  
- Final insights such as best-selling items and revenue trends are generated  

---

## 📈 Output

- Total revenue generated  
- Most frequently ordered items  
- Quantity-wise analysis of orders  
- Structured insights from raw transactional data  

---

## 🤖 Use of Generative AI

- Code generation (Mapper & Reducer)  
- Debugging assistance  
- Hive query support  
- Concept understanding  

---

## 🔐 Validation

- Manually tested  
- Verified for correctness  
- Successfully executed in Hadoop environment  

---

## 🌟 Key Features

- Scalable Big Data processing  
- Efficient handling of transactional datasets  
- Distributed computing approach  
- Insightful business analytics  

---

## 🎯 Conclusion

This project demonstrates how the Hadoop ecosystem can efficiently process and analyze large-scale transactional datasets.

By leveraging HDFS, MapReduce, and Hive, raw data is transformed into actionable insights that help businesses optimize operations and improve decision-making.

---

## 👨‍💻 Author

**Rashi Rai**  
🎓 BCA (Data Science & AI)  

---

## ⭐ Final Note

This project reflects a real-world Big Data solution where distributed computing plays a crucial role in handling large-scale data efficiently.
