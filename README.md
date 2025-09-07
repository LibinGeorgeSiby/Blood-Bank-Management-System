# 🩸 Blood Bank Management System  

A *Tkinter & CustomTkinter based desktop application* for managing blood bank operations with *MongoDB integration*.  
This project provides an intuitive GUI to manage *users, donors, donations, and blood inventory*.  

---

## 🚀 Features  

- *User Authentication*  
  - Signup with username, password, and date of birth  
  - Secure login system  

- *Dashboard*  
  - Welcome screen with quick stats (Total donors, Total donations)  
  - Easy navigation between modules  

- *Donor Management*  
  - Add new donors (name, age, gender, blood group)  
  - View donor list in tabular format  

- *Blood Donations*  
  - Record blood donations with details (donor, age, gender, blood group, units, date)  
  - Auto-update inventory based on donations  

- *Blood Bank Inventory*  
  - Real-time view of available blood units by group  
  - Collect/Borrow or Deposit blood units  
  - Validation for insufficient stock  

- *Modern UI*  
  - Built using *CustomTkinter* for a clean dark-themed interface  

---

## 🛠 Tech Stack  

- *Python* (Tkinter, CustomTkinter, Tkcalendar)  
- *MongoDB* (for persistent data storage)  
- *Pymongo* (Python driver for MongoDB)  

---

## 📦 Installation  

### Prerequisites  
Make sure you have the following installed:  
- Python 3.8+  
- MongoDB (running locally on mongodb://localhost:27017/)  

### Steps  

1. Clone this repository:  
   bash
   git clone https://github.com/yourusername/blood-bank-management.git
   cd blood-bank-management
   
2. Install dependencies:

pip install customtkinter tkcalendar pymongo

3. Start MongoDB (if not already running).

4. Run the application:

python blood.py

## 📂 Project Structure
bash
blood-bank-management/
│── blood.py        # Main application
│── README.md       # Project documentation

## 🔮 Future Enhancements

- Add role-based access (Admin vs Staff)
- Generate reports (Donor history, Blood usage trends)
- Notifications for low stock levels
- Cloud-hosted MongoDB support

🤝 Contributing

Contributions are welcome! Fork the repository and submit a pull request with improvements.

📜 License

This project is licensed under the MIT License.
