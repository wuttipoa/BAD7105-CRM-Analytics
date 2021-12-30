1.สร้าง first_purchase_table ขึ้นมา โดยการเลือก cust_code\
  1.1แปลง column shop_date ให้อยู่ในรูปแบบปีและเดือนที่มีการซื้อสินค้า year_month\
  1.2หาวันที่ซื้อสินค้าวันแรกจากการใช้ Min(Shop_date) partition by cust code\
  1.3หาคนที่เป็น new customer หรือไม่โดย compare ถ้า shop date = min(shop date) ให้นับว่าเป็น new customer แล้ว label = 1 ถ้าไม่ใช่ label = 0\
\
2.select year_month, sum จำนวน new customer ในแต่ละเดือน, count จำนวน cust_code ทั้งหมดในแต่ละ year_month\
\
3.Plot สัดส่วนระหว่าง new customer กับ old customer\
