# E-Commerce System
Product Module จัดทำโดย กลุ่ม **S.O.Pang**

## Product Services
* การสร้างรายการสินค้าใหม่ (Create)
* การดูรายละเอียดของรายการสินค้า (Read)
* การแก้ไขข้อมูลรายละเอียดของรายการสินค้า (Update)
* การลบรายการสินค้า (Delete)
* การค้นหารายการสินค้า (Search)

## Product Database (Logical Design)
![Product Database (Logical Design)](https://github.com/tanknk/E-CommerceSystem/blob/Product/assets/images/PRODUCT_DB.png)
**รายละเอียด**
1. รายการสินค้า มีการเก็บข้อมูลดังนี้
    * รหัสของรายการสินค้า (id)
    * ชื่อของรายการสินค้า (name)
    * ราคาของรายการสินค้า (price)
    * รายละเอียดของรายการสินค้า (description)
    * ยอดคงคลังของรายการสินค้า (amount)
    
**หมายเหตุ:** 1. ตาราง SHOP และ ORDER รอรายละเอียดจากกลุ่มที่ทำ Module นั้น ๆ
