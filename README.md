# **Expenses Tracker**  
A web application designed to help you manage your finances and expenses. 
![GitHub repo size](https://img.shields.io/github/repo-size/kaelkkd/expenses-tracker?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/kaelkkd/expenses-tracker?style=for-the-badge)
![Project Status](https://img.shields.io/badge/Project-In%20Progress-yellow?style=for-the-badge)

## **Getting Started**  

### **Requirements**  
- Python 3.x  
- Django 4.x  
- PostgreSQL (or your preferred database)  
- Any virtual environment manager (e.g., `venv`, `virtualenv`)  

---

### **Setup**  
Follow these steps to get the application running locally:

1. **Clone the Repository**  
   ```bash  
   git clone https://github.com/kaelkkd/expenses-tracker.git  
   cd expenses-tracker  
   ```  

2. **Set Up a Virtual Environment**  
   ```bash  
   python3 -m venv venv  
   source venv/bin/activate  # For Windows: venv\Scripts\activate  
   ```  

3. **Install Dependencies**  
   ```bash  
   pip install -r requirements.txt  
   ```  

4. **Configure the Database**  
   - Add your `.env` file in the `ept/` directory with the following details:  
     ```env  
     DATABASE_NAME=<your_database_name>  
     DATABASE_USER=<your_database_user>  
     DATABASE_PASSWORD=<your_database_password>  
     DATABASE_HOST=<your_database_host>  
     DATABASE_PORT=<your_database_port>  
     ```  
   - Alternatively, edit the database settings in `ept/settings.py` to match your preferred database configuration.

5. **Run Migrations**  
   ```bash  
   python manage.py makemigrations  
   python manage.py migrate  
   ```  

6. **Start the Development Server**  
   ```bash  
   python manage.py runserver  
   ```  

7. **Access the Application**  
   Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser.

