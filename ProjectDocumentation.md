# NFC and QR Code Supported Laboratory Access System

## 1. Introduction
**Project Name**: NFC and QR Code Supported Laboratory Access System  
**Purpose**: The purpose of our project is to facilitate and secure access to university laboratories. Students will be able to request access to laboratories via a mobile application. After receiving administrator approval, students will be able to unlock the doors using NFC or QR code technology.

## 2. Problem Definition
Current laboratory access processes are generally manual, which causes time loss and poses security risks. The aim of the project is to digitize this process and create a more secure and efficient access system. Communication between students and administrators will be provided through digital platforms, ensuring a faster and more organized process.

## 3. General Structure of the Project
- **Mobile Application (to be developed with Flutter)**: Allows students to request access to laboratories, view occupancy, and make reservations. NFC or QR code will be used to unlock doors.
- **Server (Node.js)**: Processes requests from the mobile application and communicates with the database.
- **Database (MySQL)**: Stores user information, laboratory details, reservations, and door access information.

## 4. Technical Details
**Mobile Application (Flutter)**  
Reads NFC Tag or QR code information and sends it to the server. UI/UX design is simple and user-friendly, showing building photos and lab occupancy.

**Server Side (Node.js)**  
API Structure: Processes requests using RESTful API. Real-Time Occupancy Control: Tracks laboratory occupancy in real-time.

## 5. Workflow
1. **User Login**: Students log in and request access.
2. **Making a Reservation**: Users view lab occupancy and request reservation times.
3. **Administrator Approval**: Admin approves/rejects requests. Notifications sent upon approval.
4. **Access with NFC/QR Code**: Students unlock doors using NFC or QR code.
5. **Locking System and Security**: Continuously updates occupancy status.

## 6. User Interface (UI)
- **Student Login Page**: Shows occupancy and reservation times.
- **Administrator Page**: Views occupancy and handles requests.

## 7. DevOps and System Optimization
Docker containerization for stability and load balancing. Scaling ensures efficient high-load operation.

## 8. Conclusion
The project creates a secure, digital access system for university laboratories. Future improvements include optimizing sensors for detailed data and simplifying the user interface.

