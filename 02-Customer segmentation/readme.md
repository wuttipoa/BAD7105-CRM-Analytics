1.จาก data ที่ได้มาซึ่งเป็น transaction data ต้อง transform data ให้อยู่ในรูป 1 user ต่อ 1 row ก่อนโดย aggregate feature ดังนี้\
-Total spend: Sum all spending per user\
-Totalvisits: Sum total visit per user\
-Totalprod: Unique no. of product per user\
-Shop_weekdays: The highest frequency day in week that each user come to shopping\
-Shop_hours: The highest frequency hour that each user come to shopping\
-Basket_dominant: The highest frequency product type that each user buy (e.g. Grocery, Fresh...)\
-Ticketsize: Avg. spending per time\
\
2.Run K-mean โดยการ plot elbow เพื่อให้ได้จำนวนกลุ่มลูกค้าที่มีความเหมาะสม โดยได้จำนวน group = 4\
![image](https://user-images.githubusercontent.com/77907226/147729363-21cb33df-4747-4fbb-bd65-bcef8f06e2d9.png)\

3.สรุปข้อมูลของทั้ง 4 กลุ่ม\
![image](https://user-images.githubusercontent.com/77907226/147730470-b38920f2-30f5-4f5c-8b41-4248920c41c0.png)\

4.ใช้ Tree model ในการแบ่งกลุ่ม\
![image](https://user-images.githubusercontent.com/77907226/147730533-06b0c44f-2153-454d-ba35-ac1bd34d4c76.png)\

5.สรุปการแบ่ง segment ได้ออกมาเป็น 5 กลุ่ม โดยมี action plan ของแต่ละกลุ่มดังรูป\
![image](https://user-images.githubusercontent.com/77907226/147730832-b9357849-e65b-4c63-9f1a-e254dd9dfede.png)
