# Woke AI Platform

**Premium in-house services with AI-powered matching.**  
This repository contains the Woke platform frontend and backend. Users can browse service providers, book tasks, and manage bookings. The backend uses FastAPI and Supabase for database and authentication, while the frontend is built with HTML, TailwindCSS, and JavaScript.

---

## Features

- Customer and provider registration/login.
- Browse service providers by category (Cleaning, Repairs, Beauty, etc.).
- Book services with task details linked to customer accounts.
- Review and rating system for taskers.
- Mock checkout/payment flow.

---

## Getting Started (Local Development Only)

### 1. Clone the Repository
 - Install GitHub Desktop
 - Go to File -> Clone Repository (or click Ctrl + Shift + O)
 - Click the URL section and copy and paste this link: "https://github.com/shri4anand/VTHAX25-2.git"


### 2. Setup Backend
- Type into terminal
   ```
   cd backend copy
   ```
- or right-click the folder "backend copy" and click "Open in Terminal"
   
- Create Virtual Environment : python -m venv venv
- Activate it:
 ```
venv\Scripts\activate               #  Windows
source venv/bin/activate            #  macOS/Linux
```
- Install dependencies:
  ```
  pip install -r requirements.txt
  ```
- If the step above doesn't work, copy and paste this statement into the venv:
  ```
      pip install fastapi==0.111.1
      pip install uvicorn==0.23.2
      pip install python-dotenv==1.0.1
      pip install supabase==1.0.0
      pip install pydantic==2.7.0
      pip install typing-extensions==4.7.1
      pip install requests==2.31.0
      pip install aiohttp==3.9.5
  ```

- Run your backend:
 ```
uvicorn main:app --reload
```




