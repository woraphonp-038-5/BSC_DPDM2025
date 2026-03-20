# BSC_DPDM2025
Woraphon Pontri 663020038-5

---

## **Chapter 1. Introduction**
Slide: [01Intro](https://drive.google.com/drive/folders/1p0oeCC3G1NuLLcgtQ0cM2WYAHcT41Nso)

**contents:**
* ✨ **Why Data Mining?** (ทำไมต้องมีการทำเหมืองข้อมูล?)
* 🔍 **What Is Data Mining?** (การทำเหมืองข้อมูลคืออะไร?)
* 🌐 **A Multi-Dimensional View of Data Mining** (มุมมองหลายมิติของการทำเหมืองข้อมูล)
* 💾 **What Kinds of Data Can Be Mined?** (ข้อมูลประเภทใดที่สามารถนำมาทำเหมืองได้?)
* 📊 **What Kinds of Patterns Can Be Mined?** (รูปแบบประเภทใดที่สามารถขุดค้นพบได้?)
* 🛠️ **What Kinds of Technologies Are Used?** (มีการใช้เทคโนโลยีประเภทใดบ้าง?)
* 🎯 **What Kinds of Applications Are Targeted?** (มีการประยุกต์ใช้ในด้านใดบ้าง?)
* 🛑 **Major Issues in Data Mining** (ประเด็นสำคัญ/ปัญหาหลักในการทำเหมืองข้อมูล)
* 📜 **A Brief History of Data Mining and Data Mining Society** (ประวัติโดยย่อของการทำเหมืองข้อมูลและสังคมการทำเหมืองข้อมูล)
  
*สรุป  
---

## **Chapter 2. Getting to Know Your Data**
Slide: [02Data](https://drive.google.com/drive/folders/1p0oeCC3G1NuLLcgtQ0cM2WYAHcT41Nso)

**contents:**
* 📊 **Data Objects and Attribute Types** (วัตถุข้อมูลและประเภทของแอตทริบิวต์)
* 📈 **Basic Statistical Descriptions of Data** (การอธิบายทางสถิติพื้นฐานของข้อมูล)
* 🖼️ **Data Visualization** (การแสดงข้อมูลด้วยภาพ)
* 📏 **Measuring Data Similarity and Dissimilarity** (การวัดความคล้ายและความไม่คล้ายของข้อมูล)
  
*สรุป
---

## **Chapter 3. Data Preprocessing**
Slide: [03Preprocessing](https://drive.google.com/drive/folders/1p0oeCC3G1NuLLcgtQ0cM2WYAHcT41Nso)

**contents:**
* 🛠️ **Data Quality & Overview** (คุณภาพของข้อมูลและภาพรวม): ทำความเข้าใจมิติต่างๆ ของคุณภาพข้อมูล เช่น ความถูกต้อง (Accuracy), ความครบถ้วน (Completeness), และความสอดคล้อง (Consistency) เพื่อเตรียมความพร้อมก่อนการทำเหมืองข้อมูล
* 🧹 **Data Cleaning** (การทำความสะอาดข้อมูล): การจัดการกับข้อมูลที่ไม่สมบูรณ์ (Missing values), การลดสัญญาณรบกวน (Noise), การตรวจจับและกำจัดข้อมูลที่ผิดปกติ (Outliers) รวมถึงการแก้ไขข้อมูลที่ขัดแย้งกัน
* 🔗 **Data Integration** (การรวมข้อมูล): เทคนิคการรวมข้อมูลจากหลายแหล่ง (Multiple sources) การแก้ปัญหาการระบุตัวตนของเอนทิตี (Entity Identification) และการลดความซ้ำซ้อนของข้อมูล (Redundancy)
* 📉 **Data Reduction & Transformation** (การลดรูปและการแปลงข้อมูล): 
    * **Data Reduction**: การลดขนาดของข้อมูลลงเพื่อให้ประมวลผลได้เร็วขึ้น เช่น การลดจำนวนชุดข้อมูล (Numerosity Reduction) และการบีบอัดข้อมูล (Data Compression)
    * **Data Transformation**: การปรับรูปแบบข้อมูลให้เหมาะสม เช่น การทำ Normalization และการสร้างลำดับชั้นของข้อมูล (Concept Hierarchy Generation)
* 📐 **Dimensionality Reduction** (การลดมิติของข้อมูล): การคัดเลือกหรือสกัดคุณลักษณะที่สำคัญเพื่อลดจำนวนตัวแปร เช่น การทำ Principal Component Analysis (PCA) หรือการเลือกเฉพาะแอตทริบิวต์ที่จำเป็น (Attribute Subset Selection)
  
*สรุป
---

## **Chapter 6. Mining Frequent Patterns, Association and Correlations** 
Slide: [06FPBasic](https://drive.google.com/drive/folders/1p0oeCC3G1NuLLcgtQ0cM2WYAHcT41Nso)

**contents:**
* 💡 **Basic Concepts** (แนวคิดพื้นฐาน): ความหมายของ Frequent Patterns, Association Rules (กฎความสัมพันธ์) และการวัดค่าความน่าสนใจด้วยค่า Support (ความนิยม) และ Confidence (ความเชื่อมั่น) รวมถึงรูปแบบการบีบอัดข้อมูลอย่าง Closed Patterns และ Max-Patterns
* ⛏️ **Efficient Pattern Mining Methods** (วิธีการทำเหมืองแพทเทิร์นอย่างมีประสิทธิภาพ):
    * **Apriori Algorithm**: อัลกอริทึมมาตรฐานที่ใช้หลักการ "Apriori Property" เพื่อลดขอบเขตการค้นหา (Pruning)
    * **FP-growth Algorithm**: การขุดค้นแพทเทิร์นโดยไม่สร้าง Candidate (Candidate Generation) โดยใช้โครงสร้างข้อมูลแบบ FP-tree
    * **Vertical Data Format (Eclat)**: การขุดค้นข้อมูลในรูปแบบแนวตั้ง (Transaction ID lists)
* 📉 **Pattern Evaluation** (การประเมินแพทเทิร์น): การวิเคราะห์ว่ากฎที่พบน่าสนใจจริงหรือไม่ โดยใช้การวัดความสัมพันธ์ (Correlation Analysis) และค่า Lift หรือค่าความอิสระ (Lift / Chi-square) เพื่อคัดกรองกฎที่อาจทำให้เข้าใจผิด
  
*สรุป
---

## **Chapter 8. Classification: Basic Concepts**
Slide: [08ClassBasic](https://drive.google.com/drive/folders/1p0oeCC3G1NuLLcgtQ0cM2WYAHcT41Nso)

**contents:**
* 🧩 **Basic Concepts** (แนวคิดพื้นฐาน): ความหมายของการจำแนกประเภท (Classification) ข้อแตกต่างระหว่าง Supervised Learning (การเรียนรู้แบบมีผู้สอน) และ Unsupervised Learning (การเรียนรู้แบบไม่มีผู้สอน) รวมถึงกระบวนการสร้างโมเดลและการนำไปใช้งาน
* 🌳 **Decision Tree Induction** (การสร้างต้นไม้ตัดสินใจ): อัลกอริทึมการเรียนรู้ด้วยต้นไม้ เช่น ID3, C4.5 และ CART การเลือกคุณลักษณะที่ดีที่สุดด้วยค่า Information Gain, Gain Ratio และ Gini Index รวมถึงการแก้ปัญหา Overfitting ด้วยการตัดแต่งกิ่ง (Tree Pruning)
* ⚖️ **Bayes Classification Methods** (วิธีการจำแนกแบบเบย์): ทฤษฎีบทของเบย์ (Bayes' Theorem) และ Naïve Bayes Classifier ซึ่งตั้งอยู่บนสมมติฐานความอิสระระหว่างแอตทริบิวต์ (Class Conditional Independence)
* 📈 **Linear Classifier** (ตัวจำแนกเชิงเส้น): การหาเส้นแบ่งกลุ่มข้อมูลด้วยวิธีทางคณิตศาสตร์ เช่น Linear Discriminant Analysis (LDA) เพื่อแยกคลาสออกจากกันให้ดีที่สุด
* 🎯 **Model Evaluation and Selection** (การประเมินและเลือกโมเดล): การวัดประสิทธิภาพของโมเดลด้วยค่า Accuracy, Precision, Recall และ F-measure รวมถึงเทคนิคการทดสอบอย่าง Cross-validation และการใช้ ROC Curve
* 🚀 **Ensemble Methods** (วิธีการแบบกลุ่ม): เทคนิคการเพิ่มความแม่นยำโดยการรวมหลายโมเดลเข้าด้วยกัน เช่น Bagging, Boosting และ Random Forest
  
*สรุป
---

## **Chapter 9. Classification: Advanced Methods**
Slide: [09ClassAdvanced](https://drive.google.com/drive/folders/1p0oeCC3G1NuLLcgtQ0cM2WYAHcT41Nso)

**contents:**
* 🕸️ **Bayesian Belief Networks** (เครือข่ายความเชื่อแบบเบย์): การต่อยอดจาก Naïve Bayes โดยอนุญาตให้แอตทริบิวต์มีความสัมพันธ์ต่อกันได้ผ่านโครงสร้างกราฟระบุทิศทาง (Directed Acyclic Graph - DAG) เพื่อใช้คำนวณความน่าจะเป็นในสถานการณ์ที่ซับซ้อนขึ้น
* 🛡️ **Support Vector Machines (SVM)**: อัลกอริทึมที่ทรงพลังสำหรับการจำแนกข้อมูลทั้งแบบเส้นตรงและไม่เป็นเส้นตรง โดยการหา "Hyperplane" ที่มีระยะห่าง (Margin) มากที่สุด และการใช้เทคนิค Kernel เพื่อจัดการกับข้อมูลที่มีมิติสูง
* 🧠 **Neural Networks and Deep Learning** (โครงข่ายประสาทเทียมและการเรียนรู้เชิงลึก): แนวคิดของ Multilayer Feed-Forward Networks, การปรับปรุงค่าน้ำหนักด้วย Backpropagation และการปูพื้นฐานสู่ Deep Learning เพื่อใช้จัดการกับข้อมูลที่ซับซ้อนมาก
* 🔍 **Pattern-Based Classification** (การจำแนกตามแพทเทิร์น): การใช้ Frequent Patterns ที่ขุดพบจากบทก่อนหน้ามาสร้างเป็นกฎหรือตัวจำแนกประเภทข้อมูลที่มีประสิทธิภาพ (เช่น CBA, CMAR)
  
![Pattern-Based Classification](https://www.byclb.com/TR/Tutorials/neural_networks/images/fig1.1.jpg)
* 🐢 **Lazy Learners and K-Nearest Neighbors (k-NN)**: วิธีการเรียนรู้แบบ "ขี้เกียจ" ที่จะยังไม่สร้างโมเดลจนกว่าจะมีข้อมูลทดสอบเข้ามา โดยการเปรียบเทียบความคล้ายคลึงกับเพื่อนบ้านที่ใกล้ที่สุด $k$ ลำดับ
  
![k-nearest neighbors](https://miro.medium.com/v2/resize:fit:640/format:webp/0*iaMAvcfKiMTGhtA1.png)
* 🛠️ **Other Classification Methods** (วิธีการอื่น ๆ): การใช้ Genetic Algorithms, Rough Set Approach และ Fuzzy Set Approach ในการจำแนกประเภทข้อมูล
  
*สรุป
---

## **Chapter 10. Cluster Analysis: Basic Concepts and Methods**
Slide: [10ClusBasic](https://drive.google.com/drive/folders/1p0oeCC3G1NuLLcgtQ0cM2WYAHcT41Nso)

**contents:**
* 🧩 **Cluster Analysis: An Introduction** (บทนำเกี่ยวกับการวิเคราะห์กลุ่ม): การทำความเข้าใจว่า Cluster คืออะไร (กลุ่มข้อมูลที่คล้ายกันอยู่ด้วยกัน ต่างกันอยู่แยกกัน) และความแตกต่างระหว่าง Clustering (Unsupervised) กับ Classification (Supervised)
* 📍 **Partitioning Methods** (วิธีการแบ่งส่วน): การแบ่งข้อมูลออกเป็น $k$ กลุ่มโดยตรง เทคนิคหลักคือ **k-means** (ใช้ค่าเฉลี่ยของกลุ่ม) และ **k-medoids** (ใช้จุดข้อมูลจริงเป็นตัวแทนกลุ่ม)

* 🌳 **Hierarchical Methods** (วิธีการจัดลำดับชั้น): การสร้างโครงสร้างกลุ่มแบบต้นไม้ (Dendrogram) มีทั้งแบบรวมกลุ่มจากล่างขึ้นบน (Agglomerative) และแบบแบ่งย่อยจากบนลงล่าง (Divisive)

* 🌊 **Density-Based & Grid-Based Methods** (วิธีอิงความหนาแน่นและโครงข่าย): 
    * **Density-Based**: เน้นค้นหากลุ่มที่มีรูปร่างอิสระตามความหนาแน่นของข้อมูล เช่น อัลกอริทึม **DBSCAN**
    * **Grid-Based**: แบ่งพื้นที่ข้อมูลเป็นช่องตาราง (Grid) เพื่อความรวดเร็วในการประมวลผล
* 📊 **Evaluation of Clustering** (การประเมินผลการจัดกลุ่ม): การวัดคุณภาพของกลุ่มที่ได้ ทั้งแบบใช้ข้อมูลภายนอกเทียบ (External) และการวัดความแน่นแฟ้นภายในกลุ่มเอง (Internal/Cohesion)
  
*สรุป
---

## **เอกสารเรียนรู้เพิ่มเติม**
**Link:** [Data Mining: Concepts and Techniques](https://drive.google.com/drive/folders/1T2W-gR_XMml0MQHVQKQ_Em9PndVJzZco)
<div align="center">
  <img src="https://m.media-amazon.com/images/I/71Fj5RiexsS._AC_UF894,1000_QL80_.jpg" width="300">
  <br>
  <b>Data Mining: Concepts and Techniques</b>
</div>


