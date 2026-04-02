# 🐾 Funny Paw  
### A Full-Stack Pet Service Platform for Matching Pet Owners with Pet Sitters  



## 🌟 Overview
Funny Paw is a full-stack web application designed to connect pet owners with trusted pet sitters.  
The platform supports **two user roles** and provides features such as authentication, booking, search, and reviews.

Built with **Flask + MySQL**, this project demonstrates full-stack development, backend logic design, and database integration.



## 🚀 Highlights
- 🔐 Role-based user system (Pet Owner / Pet Sitter)
- 🔍 Search & filtering for sitter discovery
- 📅 Booking & reservation system
- ⭐ Review & rating functionality
- 🗄 Persistent data storage with MySQL
- 🌐 Multi-page web app with dynamic rendering (Jinja2)



## 🛠 Tech Stack

**💻 Backend**  
- Python  
- Flask  
- SQLAlchemy  

**🎨 Frontend**  
- HTML  
- CSS  
- Jinja2  

**🗄 Database**  
- MySQL  
- PyMySQL  



## 🧩 Core Features
- 👤 User registration & authentication  
- 📝 Profile management  
- 🔍 Search and filter pet sitters  
- 📅 Booking system for pet services  
- ⭐ Review and rating system  
- 📊 Order history and booking management  



## Installation
#### Clone the repository
```Bash
git clone https://github.com/cindyhuang1013/Pet-Service-Website.git
cd Pet-Service-Website
```
#### Install dependencies
```Bash
pip install flask-wtf wtforms email_validator flask_bcrypt flask_login flask_sqlalchemy PyMySQL
```
#### Configure database
```Bash
app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql+pymysql://root:yourPassword@localhost/schema'
```
#### Initialize database
```Bash
from Petservice.models import db
from Petservice import app
app.app_context().push()
db.create_all()
```
#### Run the app
```Bash
python run.py
```


## 🤝 Team
This project was **developed collaboratively with a team at National Chengchi University as part of a database systems course.**

 👩‍💻 My Contributions
- Developed backend logic for core platform features, including user authentication, profile management, and booking workflows  
- Implemented search and filtering functionality to improve user experience in discovering pet sitters  
- Built key components of the booking system, enabling reservation and order management  
- Integrated frontend templates with backend services using Flask and Jinja2  