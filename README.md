# DeskSlot Booking System

## Overview
The **DeskSlot Booking System** is an application designed to eliminate the difficulty students face in searching for vacant and working computer systems after college hours. This application is specifically designed for use within **Shri Vishnu Engineering College for Women**. It enables students to **book and manage desk spaces** in shared computer labs and libraries, ensuring optimal resource utilization and a structured work environment.

---

## 🚀 Features  
1. **Exclusive to Our College** - The application is designed specifically for use within our institution.  
2. **Computer Seat Booking** - Students can book computers in **D-block and the Digital Library** on holidays and after college hours.  
3. **Flexible Booking System** - Users can book seats for their required time slots easily.  
4. **Easy Cancellation** - Booked seats can be canceled anytime.  
5. **Real-Time Seat Availability** - Students can view available, booked, and under-repair computers.  
6. **Admin Control** - Admins can update the status of computers under repair.  

---

## 🛠️ Installation/Setup  
1. **Create a new folder** in **VS Code** (or any preferred coding platform).  
2. **Set up a Python Virtual Environment** inside the folder.  
3. **Install Dependencies**:  
   ```bash
   py -m pip install mysql-connector-python pillow tkcalendar
   ```  
4. **Connect to MySQL Workbench** for database management.  
5. **Save required images** inside a folder named `assets`.  
6. **Save the main Python script (`deskslot.py`)** inside a folder named `source`.  
7. **Activate the Virtual Environment** and run the program:  
   ```bash
   py deskslot.py
   ```  

---

## 📌 Usage  
1. **Login as a student** using the student admission number provided by the college.  
2. **Select Date & Time Slot** for booking.  
3. **Choose Location**: **D-211 Computer Lab** or **Digital Library**.  
4. **Select Available Seats** (Grey Color indicates available seats).  
5. **Check Status**:
   - **Red** - Computers under repair.  
   - **Yellow** - Already booked.  
   - **Grey** - Available for booking.  
6. **Confirm Booking** and review slot details.  

---

## 🙏 Acknowledgements  
Special thanks to **Shri Vishnu Engineering College for Women** for their support and guidance. A heartfelt appreciation to all contributors who played a role in developing this application.

---

### 📢 Thank You!  
