# 🎓 Student Management System (Flutter + Firebase)

ระบบจัดการนักศึกษาโดยใช้ **Flutter Web** และ **Firebase Firestore**  
คุณสามารถ **เพิ่ม, แก้ไข, และลบนักศึกษา** ได้แบบเรียลไทม์ 🚀

## ตัวอย่าง
![image](https://github.com/user-attachments/assets/1fc14f33-6023-42d8-9618-20526fd11b62)
![image](https://github.com/user-attachments/assets/c267f3b1-92d8-4f02-9cbf-bb7f155bcbe6)


---

## 📌 Features
✅ **แสดงรายชื่อนักศึกษา**  
✅ **เพิ่มนักศึกษาใหม่**  
✅ **แก้ไขข้อมูลนักศึกษา**  
✅ **ลบนักศึกษา**  
✅ **รองรับ Flutter Web และ Firebase Firestore**  

---

## 🚀 วิธีติดตั้งและรันแอป
### 1️⃣ **ติดตั้ง Flutter**
คุณต้องติดตั้ง Flutter ก่อน ถ้ายังไม่มี ให้ดาวน์โหลดจาก [Flutter Official Site](https://flutter.dev/docs/get-started/install)

ตรวจสอบว่า Flutter ถูกติดตั้งแล้ว:
```sh
flutter --version
```
## ติดตั้งแพ็กเกจที่จำเป็น
## รันคำสั่งนี้เพื่อดาวน์โหลด dependencies:
-- flutter pub get

## ตั้งค่า Firebase
สร้างโปรเจค Firebase และเปิดใช้ Firestore

ไปที่ Firebase Console
  คลิก "Create Project" → ตั้งชื่อโปรเจค → กด Continue
  ปิด Google Analytics (ถ้าไม่ต้องการ) → กด Create Project
  ไปที่ Firestore Database → กด Create Database → เลือก Start in test mode
  ไปที่ Project Settings → เลือก "Your Apps" → กดปุ่ม "Add App"
  เลือก Flutter (Web) และทำตามขั้นตอน
  ดาวน์โหลดไฟล์ firebase_options.dart และวางไว้ในโฟลเดอร์ lib/

## รันแอป
📌 สำหรับ Flutter Web ให้รันคำสั่งนี้:
  flutter run -d chrome
  flutter run -d Edge
  flutter run -d chrome


## 📂 **โครงสร้างโปรเจกต์**
```
/lib
 ├── main.dart                 # จุดเริ่มต้นของแอป
 ├── StudentListPage.dart       # หน้าแสดงรายชื่อนักศึกษา
 ├── StudentFormPage.dart       # ฟอร์มเพิ่ม/แก้ไขนักศึกษา
 ├── firebase_options.dart      # ค่าคอนฟิก Firebase (Web)

```
## 🔥 เทคโนโลยีที่ใช้
Flutter (Web & Mobile)
Firebase Firestore (ฐานข้อมูลเรียลไทม์)
Material Design
Cloud Firestore Database

## 🛠 การแก้ปัญหา
## ❌ ปัญหา: Firebase ไม่ทำงาน
## ✅ วิธีแก้:

## ตรวจสอบว่า firebase_options.dart ถูกต้องหรือไม่
  flutter clean
  flutter pub get

❌ ปัญหา: Firebase SDK เวอร์ชันเก่า
✅ อัปเดต pubspec.yaml เป็นเวอร์ชันล่าสุด 

  flutter pub upgrade
  flutter pub get
