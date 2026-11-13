# SqlBro

เครื่องมือ SQL Server ตัวเบา ไฟล์เดียว: ดู/แก้ข้อมูลแบบ Excel, รัน SQL และ stored procedure, log พร้อม revert,
Find in Database, และ compare ข้อมูล/โครงสร้างระหว่างสอง database พร้อมสร้าง deploy script

A light, single-file SQL Server tool: Excel-like browse/edit, SQL and stored procedures, execution log with revert,
Find in Database, and data/structure compare with deploy-script generation.

## ดาวน์โหลด / Download

1. ติดตั้ง / Install **[.NET 9 Desktop Runtime (x64)](https://dotnet.microsoft.com/download/dotnet/9.0)** (once per PC).
2. โหลด / Download `SqlBro.exe` from the **[latest release](https://github.com/DialDogma/SqlBro/releases/latest)** and run it.

## อัปเดต / Updates

โปรแกรมเช็คเวอร์ชันใหม่ให้วันละครั้ง หรือกด **⚙ → Check for updates** แล้วกด **⬆ Update** ได้เลย
ไฟล์ที่โหลดต้องตรงกับ SHA-256 ใน `version.json` ถึงจะถูกใช้

The app checks once a day (or **⚙ → Check for updates**); **⬆ Update** downloads, verifies the SHA-256 in
`version.json`, replaces the exe and restarts.

---
repo นี้เก็บแค่ไฟล์ release (`SqlBro.exe`, `version.json`) ไม่มี source code
This repository only hosts releases; it contains no source code.
