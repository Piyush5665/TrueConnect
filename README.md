# TrueConnect

<b> TrueConnect is a cutting-edge video calling platform designed to eliminate anonymous interruptions with robust 2FA security. It combines face recognition and email password verification to ensure that only registered, verified users can join meetings. With a high accuracy of 99.38%, TrueConnect guarantees secure and authentic interactions.
<br>

## Features:

### 🔒 Advanced Security
- <b>Two-factor authentication (2FA) with 99.38% accurate face recognition and email verification.</b> <br>

### 💻 Powerful Video Conferencing

- <b>Seamless group calls for 50+ users.
- <b>In-meeting chat functionality.
- <b>One-click screen sharing.


### ☁️ Cloud-Powered

- Cloud storage for all data - no local DB needed.
- GridFS implementation for large size mage storage.

### 📱 Progressive Web App (PWA)

- Download and add to homescreen/desktop for ease of access.
- Smooth installation, native-like behaviour and access to device hardware.

### 🔑 Authentication
- Quick login via Gmail.
- Auth check in meet to prevent unauthorized users from entering.

### 👥 User-Centric Design

- Intuitive interface tailored for Gen Z.
- Hassle-free registration and meeting setup.

<!--
### 👤 Real People Only
- Say goodbye to anonymous interruptions and unwanted guests <br> 
### 📸 Highly Accurate
- Built with the help of Face Recognition Library in Python, it gives an accuracy of <b>99.38%<b>.
### 🚀 Easy Setup 
- Register with email, password, and photo to start hosting or joining meetings <br>
### 🛡️ Verified Attendance 
- Face verification ensures real individuals are present <br>
### 💻 User-Friendly 
- Designed for the Gen Z audience <br>
### 🔑 Access Control 
- Only registered and verified users can join meetings <br>
### 🌐 Seamless Integration
- Built for modern, secure video communication needs <br>
### ⚡ Efficient Process
- Quick registration and verification for hassle-free meetings <br>
### 🔐 Privacy First
- Prioritizing user data protection and meeting security <br>
-->
<br>

## Tech Stack:
1. Front End / Client Side
    - ReactJS 
    - Bootstrap - CSS and other components.
    - React Webcam - Capture user's image.

2. BackEnd Server:
   - For Face Recognition
     - Face Recognition Library - Calculate encodings.
     - Open CV - Compare images based on encodings.
   
   - For video calling
      - Twilio Video API - Create Real-Time Video App.
      - Twilio Cloud - Connect room participants.

3. Data Management (Databases): 
    - MongoDB Atlas - Data management and user details
    - Grid FS - Storing image with base64 data.
  
<br>

## Installation


### Pre-Requisites:
1. Install Git Version Control
[ https://git-scm.com/ ]

2. Install Python Latest Version
[ https://www.python.org/downloads/ ]

3. Install Pip (Package Manager)
[ https://pip.pypa.io/en/stable/installing/ ]

4. Install MongoDB Compass and connect it to localhost **27017** [ Atlas Connection is quite slow and may not work everytime ]
- Uncomment the following code in app.py to change the connection as per requirement.

  <img src="https://user-images.githubusercontent.com/85401522/183743315-a766d3a9-f7ff-4797-a162-68849f134134.png" alt="Faa" border="0" width=400>




### Clone the project:

```bash
  git clone https://github.com/Piyush5665/TrueConnect.git
```

Go to the project directory

```bash
  cd TrueConnect
```

**Backend Server:**

Go to backend folder

```bash
  cd backend
```
#### Create a Virtual Environment and Activate:

Install Virtual Environment

```bash
  pip install virtualenv
```

Create Virtual Environment:


```bash
  virtualenv venv
```

Go to venv folder and Activate virtual enviroment

```bash
  cd venv
```
Run the following command
```bash
  .\Scripts\activate.ps1
```
Go back to backend folder
```bash
  cd ..
```
Install Requirements from 'requirements.txt'
```bash
  pip install -r requirements.txt
```

Start the backend server

```bash
 flask run
```

**Frontend Server:**

Go to frontend folder

```bash
 cd frontend
```

Install all dependencies

```bash
 npm install
```
Start frontend server

```bash
 npm run start
```

#### Local Url for Server:

- Frontend is running on http://localhost:3000 
- Backend is running on http://127.0.0.1:5000

  <br>
  
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

```
TWILIO_ACCOUNT_SID=AC612f9ab098d697e6d572725234130052
TWILIO_API_KEY_SID=SKf1a116bd7f1c50a6e6988e875c9b85a2
TWILIO_API_KEY_SECRET=YPe9sOZP25xzUxnMd6xLXBKfigNmTJRC
```


















