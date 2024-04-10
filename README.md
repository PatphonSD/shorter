## ยินดีต้อนรับสู่ URL Shorter!

โปรเจคนี้มุ่งเป้าไปที่การสร้าง URL Shorter ง่ายๆ โดยใช้ T3-stack ร่วมกับ prisma sqlite typescript โปรเจคนี้เปิดกว้างสำหรับทุกคน  contribute  ได้ 

### คุณสมบัติ

* ย่อ URL ยาวๆ ให้สั้นลง
* รองรับการตั้งค่า custom alias
* แสดงสถิติการคลิก
* ใช้งานง่าย
* โค้ดโอเพ่นซอร์ส

### เริ่มต้นใช้งาน

1. โคลนโค้ดจาก Github:

```
git clone https://github.com/PatphonSD/shorter.git
```

2. ติดตั้ง dependencies:

```
npm install
```

3. ตั้งค่า database:

```
npx prisma migrate dev
```

4. รันโปรเจค:

```
npm start
```

### การใช้งาน

* ไปที่หน้าเว็บ: `http://localhost:3000`
* ใส่ URL ที่ต้องการย่อ
* คลิกปุ่ม "ย่อ URL"
* URL ที่ย่อแล้วจะแสดงขึ้นมา
* คุณสามารถตั้งค่า custom alias ได้
* คลิกลิงก์เพื่อดูสถิติการคลิก

### การ Contribute

โปรเจคนี้เปิดกว้างสำหรับทุกคน  contribute  ได้ คุณสามารถ:

* รายงานบั๊ก
* เสนอแนะฟีเจอร์ใหม่
* พัฒนาโค้ด

### แหล่งข้อมูล

* T3-stack: [https://create.t3.gg](https://create.t3.gg)
* prisma: [https://www.prisma.io/](https://www.prisma.io/)
* sqlite: [https://www.sqlite.org/](https://www.sqlite.org/)
* typescript: [https://www.typescriptlang.org/](https://www.typescriptlang.org/)

ขอบคุณที่ใช้ URL Shorter! 
