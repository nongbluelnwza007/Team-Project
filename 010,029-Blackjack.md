## link youtube 
[https://youtu.be/Efc5j5Ptp9Q?si=TbGt3d-DY8Aa3kkr](https://youtu.be/HaDN3cN6YlU)

## Repo ของงานที่ทำ
[https://github.com/nongbluelnwza007/Blackjack-OOP.git](https://github.com/nongbluelnwza007/Blackjack-OOP)


# จัดทำโดย

1.นาย กันตพัฒน์ ตั้งกิตติธารา 66030010

2.นางสาว จิรสิน วรศิริ 66030029

## เนื้อหาภายในคลิป

โค้ดนี้เป็นตัวอย่างของแอปพลิเคชันเกม Blackjack ที่พัฒนาด้วย Windows Forms โดยนำหลักการของ Object-Oriented Programming (OOP) มาใช้เพื่อให้โค้ดมีโครงสร้างที่ดีขึ้น ง่ายต่อการบำรุงรักษาและขยายผล

### หลักการ OOP ที่ถูกนำมาใช้

## Encapsulation (การห่อหุ้ม):

มีการแยกข้อมูล (Attributes) และพฤติกรรม (Methods) ออกจากกันในคลาสต่างๆ เช่น Card, Deck, Player, Dealer, และ Game ทำให้โค้ดมีความเป็นระเบียบ
ใช้ Access Modifiers (private, public) เพื่อควบคุมการเข้าถึงข้อมูล เช่น Deck มีเมธอด Shuffle() และ DrawCard() เพื่อให้เฉพาะ Game เท่านั้นที่สามารถเข้าถึงได้
ป้องกันการแก้ไขค่าของการ์ดโดยตรงจากภายนอกคลาส ด้วยการกำหนดให้ฟิลด์เป็น private และเข้าถึงผ่าน Properties

## Abstraction (การนามธรรม):

มีการสร้างอินเทอร์เฟซ ICardGame ที่กำหนดสัญญาว่าเกมไพ่ต้องมีฟังก์ชัน StartGame(), EndGame(), และ GetWinner()
คลาส Game ซ่อนรายละเอียดการทำงาน เช่น การแจกไพ่ การคิดคะแนน และการตรวจสอบผลลัพธ์ ให้ผู้ใช้สามารถเรียกใช้เมธอดที่กำหนดไว้โดยไม่ต้องทราบกระบวนการภายใน

## Polymorphism (ความหลากหลาย):

การใช้ List<Card> ในการเก็บไพ่ของ Player และ Dealer ทำให้สามารถใช้เมธอดเดียวกันในการเพิ่มและแสดงไพ่ของทั้งสองฝ่าย
เมธอด CalculateScore() ถูก override ใน Dealer เพื่อเพิ่มเงื่อนไขพิเศษ เช่น การจั่วไพ่จนกว่าคะแนนจะถึง 17

การนำหลักการ OOP มาใช้ในโค้ดนี้ช่วยให้โครงสร้างของแอปพลิเคชันมีความยืดหยุ่น ง่ายต่อการขยายผล และลดปัญหาโค้ดซ้ำซ้อน ซึ่งเป็นแนวทางที่ดีในการพัฒนาโปรแกรมที่มีขนาดใหญ่ขึ้นในอนาคต

![Editor _ Mermaid Chart-2025-03-31-091408](https://github.com/user-attachments/assets/32cb989a-55a5-4055-924d-18d54f7e4246)

