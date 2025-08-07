# 🧾 IIUI Lost & Found Item Management System

A complete **Lost and Found Management System** designed using Microsoft Access as part of the **CS 242 – Database Systems** course at **International Islamic University Islamabad (IIUI)**.

> Semester Project | F23 | Department of CS & IT  
> Supervised by: Mr. Imran Saeed  
> Developed by: Wahab Ejaz, Abuzar Amir, Zarar Moaviya

---

## Overview
This system digitizes the process of managing lost and found items across the IIUI campus. It is a standalone desktop database application built in **Microsoft Access**, featuring relational tables, normalized data, input forms, dynamic queries, and printable reports.

---

## Features
- Add, search, and update lost/found item records
- Admin claim verification and approval
- Printable reports for found items, claims, etc.
- Structured relational database with ERD & normalization
- User-friendly main menu and form navigation

---

## Tech Stack
- Microsoft Access (.accdb)
- SQL queries (static & dynamic)
- Forms and Reports
- Normalized DB (3NF)

---

## Entity Overview
- `Admin(AdminID, Username, Password, PhoneNo, Email)`
- `Student(RegNo, StudentName, Email, ContactNo, Department)`
- `Item(ItemID, ItemName, Category, Description, Color)`
- `FoundItem(FoundID, ItemID, FounderContact, FoundDate, LocationID)`
- `LostItem(LostID, ItemID, RegNo, LostTime, LocationID)`
- `Claim(ClaimID, ClaimDate, RegNo, LostID, FoundID, AdminID)`
- `Location(LocationID, PlaceName, Floor, Description)`

---

## ERD & Normalization
The system is fully normalized (3NF), ensuring no data redundancy.  
✔️ All tables have atomic values  
✔️ Proper foreign key relationships  
✔️ One-to-many and one-to-one relationships well handled

**[ERD Diagram Preview]**  
*(see screenshots below)*

---
## Demo Video
[Click here](https://www.linkedin.com/posts/wahab-ejaz-025821283_semesterproject-lostandfoundsystem-msaccess-activity-7335581676649046016-rFxr?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAET_uN0BcIvAcZWxWDuCqYgZxpVojNFCYHw)

## Screenshots

### Main Menu  
![Main Menu](screenshots/main-menu.png)

### Add New Item Form  
![Add Item Form](screenshots/form-add-item.png)

### Report – Found Items  
![Report](screenshots/report-found-items.png)

### Entity-Relationship Diagram (ERD)  
![ERD](screenshots/erd-diagram.png)

---

## Future Enhancements

- Add login system for Admin/Student
- Rebuild with MySQL/SQLite and Web UI
- Mobile version using Flutter
- Cloud-based version with real-time search and claim

---

## 📁 Project Structure

