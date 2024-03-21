# BSC_DPDM23
Data Preparation and Data Mining
<br/><br/>
Slide&File &emsp; [Go🚀](https://drive.google.com/drive/folders/1pCDUzbfNkLg6xSxc4Pjk1UU6MrZST5rS?usp=sharing) <br/><br/>

# Me
🐱 &emsp; Phuris Kruacharee (ภูริศ เครือชารี) __643020514-7__

## Score
- Midterm (data prepocessing ปฏิบัติ (เดี่ยว))  ![](https://geps.dev/progress/20)
- Final(ทฤษฎี data mining เดี่ยว)  ![](https://geps.dev/progress/20)
- Project(data prepocessing + data mining (กลุ่ม))  ![](https://geps.dev/progress/30)
- Homework(แบ่งกลุ่มใหม่ทุกครั้ง)  ![](https://geps.dev/progress/20)
- Quiz(เดี่ยว ถามในห้อง)  ![](https://geps.dev/progress/5)
- GitHub  ![](https://geps.dev/progress/5)

Final Score = Score * %attendance 
![](https://geps.dev/progress/100)



## Homework
📝 &emsp;[Hw.1](https://github.com/PhurisKR/BSC_DPDM23/tree/main/HW_1) <br/><br/>
📝 &emsp;[Hw.2](https://github.com/PhurisKR/BSC_DPDM23/tree/main/HW_2) <br/><br/>
📝 &emsp;[Hw.3](https://github.com/PhurisKR/BSC_DPDM23/tree/main/HW_3) <br/><br/>
📝 &emsp;[Hw.4](https://github.com/PhurisKR/BSC_DPDM23/tree/main/HW_4) <br/><br/>
📝 &emsp;[Hw.5](https://github.com/PhurisKR/BSC_DPDM23/tree/main/HW_5) <br/><br/>



## Quiz
- [Quiz(All)](https://github.com/PhurisKR/BSC_DPDM23/tree/main/Quiz)


## Midterm
- [เตรียมข้อมูลอุตุนิยมวิทยา](https://github.com/PhurisKR/BSC_DPDM23/blob/main/midterm_bscdpdm23_phuris.ipynb)

## Project
- [Project Decision tree](https://github.com/PhurisKR/BSC_DPDM23/tree/main/Final)
- [WebApp_Predict_From_Decision tree](https://github.com/PhurisKR/Predict_Fake_News)
 # Data mining
 
  ## Knowledge Discovery (KDD) Process
 ![image](https://github.com/phurisk/BSC_DPDM23/assets/137043070/4440bd5e-39c1-4ed8-bcbb-191ce43f82a6)

 
- (__Data Cleaning__) การทำความสะอาดข้อมูล : การกำจัดข้อมูลที่ไม่ต้องการหรือไม่เกี่ยวข้อง เช่น โค้ด HTML, สคริปต์ JavaScript หรือข้อมูลที่ซ้ำซ้อน เพื่อให้เหลือแต่ข้อมูลที่เป็นประโยชน์เพื่อนำวิเคราะห์.

- (__Data Integration__) การรวมข้อมูลจากแหล่งต่างๆ : การรวมข้อมูลที่มาจากหลายแหล่ง หรือหลายหน้าเว็บ เพื่อสร้างมุมมองที่ครอบคลุมและสมบูรณ์.

- (__Data Warehouse__) คลังข้อมูล  : การสร้างคลังข้อมูลเพื่อเก็บข้อมูลที่ได้มา โดยจะมีการออกแบบโครงสร้างของคลังข้อมูลเพื่อรองรับการวิเคราะห์ข้อมูลในอนาคต.

- การสร้าง __Data Cube Construction__: สร้างโครงสร้างข้อมูลหลายมิติ เพื่อให้สามารถวิเคราะห์ข้อมูลได้ในหลายมิติและหลายระดับ.

- __การเลือกข้อมูลสำหรับ Data Mining__: คัดเลือกข้อมูลที่เหมาะสมและเกี่ยวข้องกับเป้าหมายของการทำเหมืองข้อมูล โดยข้อมูลนี้จะถูกนำไปใช้ในขั้นตอนถัดไป.

- (__Data Mining__) การใช้เทคนิคและอัลกอริทึมในการทำData Mining เพื่อค้นหารูปแบบ, ความสัมพันธ์, หรือความรู้ที่ซ่อนอยู่ในข้อมูล.

- (__Pattern Evaluation__) การนำเสนอผลการทำ Data Mining: การนำเสนอผลลัพธ์ของการทำเหมืองข้อมูลในรูปแบบที่เข้าใจง่าย เช่น รายงาน, แผนภูมิ, หรือการแสดงผลในรูปแบบกราฟิก เพื่อให้ผู้ใช้สามารถเข้าใจและใช้ประโยชน์จากข้อมูลให้ได้มากที่สุด.



# Normalization

![image](https://github.com/phurisk/BSC_DPDM23/assets/137043070/59859ef0-f33b-4908-a900-dbae849a4011)
- Min-max normalization: เป็นการปรับขนาดข้อมูลอยู่ในช่วงใหม่ที่กำหนด โดยที่ค่าต่ำสุดและสูงสุดของข้อมูลจะถูกแปลงไปเป็นค่าใหม่ที่กำหนด เช่น ค่า 0,1

![image](https://github.com/phurisk/BSC_DPDM23/assets/137043070/b18d3306-f8fb-4ef0-a97b-ebf00a1ba38b)
- Z-score normalization: เป็นการปรับขนาดข้อมูลโดยใช้ค่าเฉลี่ย (μ) และส่วนเบี่ยงเบนมาตรฐาน (σ) ของข้อมูล เช่น ค่า Z-score

![image](https://github.com/phurisk/BSC_DPDM23/assets/137043070/5bb14a8c-a772-4f10-ab94-f261904dbc46)
- Normalization by decimal scaling: การปรับขนาดข้อมูลโดยการเลื่อนจุดทศนิยมของข้อมูล จำนวนทศนิยมที่เลื่อนขึ้นอยู่กับค่าสูงสุดของข้อมูลที่ได้ เช่น ข้อมูลมีค่า -945 ถึง 900 จากนั้นนำค่าสัมบูรณ์ที่มากที่สุดของข้อมูล ดังนั้นจึงนำ -945 มาหาร 1000 เนื่องจาก j = 3 โดยที่ j มาจากการประมาณค่าจาก log ฐาน 10 ของ |-945| 





# Example training data set
![image](https://github.com/PhurisKR/BSC_DPDM23/assets/118201161/4f6cd41b-05b7-43ea-88e4-b74047c9c24a)


# Decision Tree
![Blank diagram](https://github.com/phurisk/BSC_DPDM23/assets/137043070/f76cb092-fd0e-441b-814a-c29cac92d121)

- Root Node: โหนดแรกสุดของโครงสร้างต้นไม้ตัดสินใจ
- Branch: เส้นที่เชื่อมระหว่างโหนดหนึ่งไปยังอีกโหนดหนึ่ง แทนการตัดสินใจหรือเงื่อนไข และนำไปสู่โหนดย่อยต่อไป
- Leaf Node: โหนดสุดท้ายในต้นไม้การตัดสินใจ แสดงผลลัพธ์หรือการตัดสินใจสุดท้าย


# Example  K-means clustering

![image](https://github.com/phurisk/BSC_DPDM23/assets/137043070/0fb484a3-2996-4622-8d4a-b8754c0c972f)



- 1: กำหนดจำนวนกลุ่มขึ้นมาก่อนเช่น 2 กลุ่มหรือหมายความว่าค่า K=2  (กำหนดเป็น C1 และ C2) และสุ่มตำแหน่งแกน x,y ให้กับ C1  และ C2 จะได้  C1(x1,y1) และ C2(x2,y2)

- 2: ดูตำแหน่งของสมาชิกแต่ละสมาชิกว่าอยู่ใกล้ใครมากกว่ากันก็ให้คนนั้นเป็นสมาชิกของ C นั้น จากตรงนี้เราจะรู้แล้วว่าสมาชิกแต่ละคนอยู่ในกลุ่มใดระหว่าง C1 และ C2

- 3: ปรับ x,y ของ C1 และ C2 ใหม่ให้อยู่ตรงกลางของกลุ่ม

- 4: ทำตามข้อ 2 และข้อ 3 อีกครั้งจนกว่า C1 และ C2 ตำแหน่งไม่เปลียน


# Flowchart of a supervised machine learning example

![image](https://github.com/PhurisKR/BSC_DPDM23/assets/118201161/13367eba-0cc2-49b0-94b4-4876d26955ec)

1. ชุดข้อมูลเริ่มต้น (Initial Dataset): ข้อมูลจะมีค่าจริงของสิ่งที่เราต้องการคาดการณ์ หรือมี Features และ Target varible (X,y)
2. การแบ่งชุดข้อมูล (Data Split): ชุดข้อมูลจะถูกแบ่งออกเป็น 2 ส่วน
 2.1 จากภาพจะแบ่ง ชุดข้อมูลฝึก (Training Set) 80% ของข้อมูลเริ่มต้น: ใช้สำหรับฝึกอบรมโมเดล Machine Learning
 2.2 ชุดข้อมูลทดสอบ (Test Set) 20% ของข้อมูลเริ่มต้น: ใช้สำหรับทดสอบประสิทธิภาพของโมเดล
3. โมเดล Machine Learning: ทำหน้าที่เรียนรู้จากชุดข้อมูลฝึกอบรม เพื่อสร้างโมเดลสำหรับคาดการณ์สิ่งที่เราสนใจ
4. การประเมินประสิทธิภาพ (Performance Evaluation): ประเมินประสิทธิภาพของโมเดล Machine Learning โดยใช้ชุดข้อมูลทดสอบ
  <br/><br/>
  **หมายเหตุ  ข้อมูลในภาพเป็นตัวอย่างเท่านั้น การใช้งานจริงอาจแตกต่างกันไป และยังมีรายละเอียดเพิ่มเติมเกี่ยวกับกระบวนการ ซึ่งไม่ได้อยู่ในภาพนี้*
 
