# 📦 Stock Management System GUI
A comprehensive **Python + Tkinter desktop application** for managing inventory and stock operations.  
This system provides an intuitive graphical interface, modular architecture, and reliable data storage designed for efficient stock control, analytics, and business intelligence.

## 🚀 Project Overview
The **Stock Management System GUI** streamlines inventory processes for businesses of all sizes.  
It offers real-time stock tracking, advanced search and filtering, automated reporting, and data-driven analytics — all built using beginner-friendly Python functionalities with a clean architectural structure.

## 📁 Project Structure
| File Name               | Description                                        |
|-------------------------|----------------------------------------------------|
| **data_operations.py**   | Core data handling and product CRUD operations     |
| **inventory_manager.py** | Inventory logic, stock tracking, and alerts        |
| **search_filters.py**    | Search, filtering, and sorting functionalities     |
| **data_persistence.py**  | File I/O, saving/loading data, and backups         |
| **calculations.py**      | Inventory analytics and financial calculations     |
| **validation_utils.py**  | Input validation and data integrity checks         |
| **main_integration.py**  | GUI implementation and full system integration     |
| **requirements.txt**     | Required libraries and dependencies                |
| **sample_data.txt**      | Sample inventory dataset                           |
| **README.md**            | Project documentation                              |

## 🛠 Technology Stack
- **Programming Language:** Python 3.8+
- **GUI Framework:** Tkinter (built-in)
- **Storage Format:** CSV-style text files
- **Architecture:** Modular, scalable, and easy to maintain

## 👥 Team Structure & Responsibilities
### 🔹 Team Leader
**Name:** **Ahmed Medhat**  
**Module:** `main_integration.py`  
**Responsibilities:**
- GUI design and implementation  
- System integration across all modules  
- Architecture planning  
- Cross-module coordination and testing  
- Advanced error handling  
- UX/UI optimization  

### 🔹 Team Members (Python Developers)
| Member Name        | Module               | Focus Area        | Key Tasks |
|--------------------|----------------------|-------------------|-----------|
| **Ahmed Medhat**   | `main_integration.py` | GUI & Integration | Full GUI, module linking, architecture |
| **Youssef Ahmed**  | `data_operations.py`  | Data Structures   | Product CRUD, list/dict operations |
| **Mariam**         | `inventory_manager.py`| Business Logic    | Stock updates, low-stock alerts, valuation |
| **Rana**           | `search_filters.py`   | Searching         | Search, sorting, filtering |
| **Lojain Mohammed**| `data_persistence.py` | Storage           | File I/O, import/export, backups |
| **Marwan**         | `calculations.py`     | Analytics         | Pricing, profit, metric calculations |
| **Abdelrahman**    | `validation_utils.py` | Data Integrity    | Input validation & error prevention |

Each member focuses ONLY on their module using basic Python (loops, functions, if-conditions, lists, dicts).

## 💡 Core Features
### 📦 Inventory Management
- Add, edit, and delete products  
- Real-time stock quantity updates  
- Low-stock alerts  
- Inventory valuation calculations  

### 🔍 Search & Filtering
- Search by product name or ID  
- Filter by price, quantity, or category  
- Multi-criteria sorting  
- Combined advanced search options  

### 📊 Analytics & Reporting
- Total inventory value  
- Profit margin analysis  
- Stock-level insights  
- Exportable reports  

### 💾 Data Persistence
- Auto-save mechanism  
- Import/export inventory data  
- Data backup & recovery  
- CSV-style readable file format  

### ✅ Data Validation
- Input sanitization  
- Business rule enforcement  
- Error detection & prevention  
- Data integrity checks  

## 🧩 Key Technical Features
- **Modular Architecture:** Each module handles a single responsibility  
- **Separation of Concerns:** Logic separated from presentation  
- **Scalable Design:** Easy to extend and maintain  
- **Robust Error Handling:** Prevents crashes and data loss  
- **User-Friendly GUI:** Clean, simple, and intuitive interface  

## 🚦 Getting Started
### ✔ Prerequisites
- Python **3.8+**
- Tkinter (included with Python on Windows/macOS)

### ✔ Installation
1. Download or clone the project directory  
2. Ensure all `.py` files are in the same folder  
3. Run the system using:

## 📘 Usage Guide
1. Launch the application via `main_integration.py`  
2. Add products using the Product Management panel  
3. Manage stock in the Inventory section  
4. Search and filter items through the Search Interface  
5. Generate reports from the Analytics section  
6. Export data for external use  

## 🔧 Module Specifications
### `data_operations.py`
- Handle product dictionary/list operations  
- CRUD (Create, Read, Update, Delete)  
- Product retrieval functions  

### `inventory_manager.py`
- Track stock levels  
- Low-stock alerts  
- Inventory valuation  
- Availability checks  

### `search_filters.py`
- Keyword search  
- Price & quantity filtering  
- Sorting (name, price, stock, etc.)  

### `data_persistence.py`
- Save and load inventory data  
- Import/export functions  
- Backup and recovery mechanisms  

### `calculations.py`
- Financial & statistical functions  
- Profit/margin calculations  
- Total inventory value  

### `validation_utils.py`
- Input validation  
- Error checking  
- Rule enforcement  

## 🎨 GUI Highlights
- Dashboard with key metrics  
- Full product management interface  
- Search & filtering view  
- Reporting & analytics interface  
- Settings & configuration panel  

## 🤝 Development Workflow
### For Team Members:
- Work ONLY on your assigned module  
- Use simple Python concepts (loops, conditions, functions)  
- Test your functions independently  
- Follow naming conventions and clean code practices  

### For Team Leader:
- Integrate all modules  
- Build & optimize the GUI  
- Ensure compatibility across components  
- Conduct system testing  

## 📈 Future Enhancements
- Barcode scanning support  
- Multi-user authentication  
- Cloud sync functionality  
- Advanced charts and visual analytics  
- Mobile companion application  
- API integration for e-commerce systems  

## 🐛 Troubleshooting
### Common Issues:
- **File permissions:** Ensure write access for data files  
- **Missing modules:** Verify all `.py` files are in the same directory  
- **Corrupted data:** Restore from backup file  
- **Python errors:** Confirm Python 3.8+ installation  

## 📄 License
This project is developed for **educational and business purposes**.  
All rights reserved by the development team.

### **Development Team • Stock Management System GUI • Version 1.0**  
- **Data Operations:** Youssef Ahmed  
- **Inventory Management:** Mariam  
- **Search Filters:** Rana  
- **Data Persistence:** Lojain Mohammed  
- **Calculations:** Marwan  
- **Validation Utils:** Abdelrahman  
- **Main Integration & GUI:** Ahmed Medhat