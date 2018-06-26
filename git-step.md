# Git Step

## Clone Repository ก่อน
```bash
git clone <url_repository>
```

## ดูสถานะของ Git ตอนนี้
```bash
git status
```

## Track ไฟล์เข้าไปยัง Git
```bash
git add <filename>
```

## เพิ่มไฟล์เข้าไปใน Git
```bash
git commit -m "message"
```

## ดึงลงมาจาก Remote Server
```bash
git pull origin master
```

## เมื่อ Pull ลงมาใหม่ให้ทำการ Run Test ก่อนเสมอ
- Unit Test
- Acceptance Test UI
- Acceptance Test API

## อัพขึ้นไปเก็บไว้บน Remote Server
```bash
git push -u origin master
```
