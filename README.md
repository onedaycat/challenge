# challenge


## ระบบสั่งอาหารออนไลน์

- ลูกค้าสามารถดูรายการอาหารได้
- ลูกค้าสามารถเลือกอาหารใส่ลงในตะกร้าได้
  - ถ้าสินค้าในคลังเหลือ 0 ไม่สามาถเลือกใส่ลงในตะกร้าได้
- ลูกค้าสามารถนำสินค้าในตะกร้ามาชำเงินผ่านบัตรเครดิตได้
  - เมื่อชำระเงินแล้วสินค้าในคลังต้องลดลง
- ลูกค้าสามาถดู order ย้อนหลังได้

## เงื่อนไขในการพัฒนา

- ให้ implement ส่วน business logic และ UI แยกจากกันอย่างชัดเจน
  - Business logic ให้เขียนด้วย DDD
  - พัฒนา UI แล้วแต่ถนัดไม่จำเป็นต้อง MVC หรือ MVVM หรือ UI ผ่าน Console หรือไม่ทำก็ได้
- UI (หรือ Controller) ต้องสื่อสารกับ business logic ผ่าน Service เท่านั้น
- ระบบต้องเก็บข้อมูลลงใน Memory หรือ Local Storage หรือ Firebase
- เขียนเทสในส่วนของ DDD ให้ coverage code 100%
- เมื่อพัฒนาเสร็จนำ Code ขึ้น Github แล้วส่งลิ้งมาที่ usawasan@onedaycat.com


![Design](https://github.com/onedaycat/challenge/raw/master/design.png)
