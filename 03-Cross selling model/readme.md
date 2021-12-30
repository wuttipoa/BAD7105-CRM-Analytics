1.install mlxtend, import apriori, association_rules\
2.Clean data โดยการ drop na, delete column timestamp\
3.Run apriori โดยใช้ minimum support = 10%\
4.Run association rules ออกมาโดยได้ผลลัพธ์ดังตารางด้านล่าง\
![image](https://user-images.githubusercontent.com/77907226/147731737-6ad246cd-533c-49d5-b3fb-b595295c55fc.png)\
จากตารางพบว่า lift กับ confidence ของ row3 มี confidence กับ lift ค่อนข่างสูง ดังนั้นจึงสรุปได้ว่า การซื้อเครื่องซักผ้ากับเครื่องอบผ้ามักเกิดคู่กัน
