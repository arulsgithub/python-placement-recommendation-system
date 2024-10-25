# Job Placement Recommendation System 🎯

A Flask-based web application that provides personalized job recommendations using machine learning algorithms. The system serves both job seekers and recruiters, creating an efficient bridge between talent and opportunities.

## 🌟 Features

### For Job Seekers
- User registration and authentication
- Personalized job recommendations based on:
  - Skills
  - Experience level
  - Job title preferences
- Track and view recommendation history

### For Recruiters
- Secure company login portal
- Access to job listings
- View recommended candidates for positions
- Manage job postings

## 🛠️ Technology Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python (Flask)
- **Database:** PostgreSQL
- **Machine Learning:** 
  - Pandas
  - NumPy
  - Scikit-learn
- **Operating System:** Linux

## 📋 Prerequisites

- Python 3.x
- PostgreSQL
- pip package manager

## 🚀 Installation and Setup

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/python-placement-recommendation-system.git
cd python-placement-recommendation-system
```

2. **Install required packages**
```bash
pip install flask psycopg2-binary pandas scikit-learn numpy werkzeug
```

3. **Database Setup**
```sql
CREATE DATABASE placement;
```
- Set PostgreSQL password to 'project'
- Execute the SQL statements from 'companies_table.txt' to create and populate the companies table

4. **Run the application**
```bash
python3 app.py
```

## 📁 Project Structure

```
├── app.py                 # Main Flask application
├── jobs1.py              # Job recommendation logic
├── jobs_info.csv         # Job dataset
├── companies_table.txt   # SQL statements for companies table
└── templates/            # HTML templates
```

## 🎯 Usage

1. Visit `http://localhost:5000` in your web browser
2. Click "Get Started" and select your role

### For Job Seekers:
- Sign up or log in with your credentials
- Click "Recommend jobs for me" to get personalized recommendations
- View your top 10 job matches based on your profile

### For Recruiters:
- Log in using company ID and password
- Access candidate listings and job postings
- Manage company job listings

## 💾 Database Schema

### Companies Table
- company_id
- company_pwd
- company
- domain

### UserInfo Table
- User registration details
- Profile information

### Recommendations Table
- Stores user-specific job recommendations
- Tracking of recommendation history

## 🔒 Security Features

- Password hashing for user accounts
- Secure session management
- Protected recruiter portal

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- Arulmurugan S
