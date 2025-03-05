# 🧘‍♂️ Real-Time Yoga Tracking System
This project is a **Flask-based Yoga Tracking System** that provides **AI-assisted pose correction** using **MediaPipe** and allows **users to track their yoga progress**.

## 🚀 Features
### 1️⃣ User Features
- ✅ **Login & Signup** - Secure authentication for users  
- ✅ **Yoga Pose Selection** - Users can choose a yoga pose to track  
- ✅ **Real-Time Pose Correction** - AI detects incorrect postures & provides feedback  
- ✅ **Track Progress** - Users can view their past practice sessions  
- ✅ **Leaderboard** - Compete with others based on time spent practicing  

### 2️⃣ Admin Features
- ✅ **Dashboard** - View total users, asanas, and engagement  
- ✅ **Manage Asanas** - Add, edit, and delete yoga poses  
- ✅ **Leaderboard for Users** - Monitor top users  
- ✅ **Export Data** - Download user performance as CSV  
- ✅ **Analytics** - Weekly & Monthly user activity trends  

---

## 🛠️ Tech Stack
### Backend
- Python Flask 🐍
- SQLAlchemy (Database ORM)
- SQLite / PostgreSQL
- MediaPipe (AI Pose Detection)

### Frontend
- HTML, CSS, JavaScript
- Tailwind CSS 🎨
- Chart.js 📊 (For Analytics & Graphs)

---

## 📦 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/yoga-tracker.git
cd yoga-tracker
```

### 2️⃣ Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Set Up the Database
```bash
flask db init
flask db migrate -m "Initial Migration"
flask db upgrade
```

### 5️⃣ Run the Application
```bash
flask run
```
✅ **Now open:** `http://127.0.0.1:5000` in your browser.

---

## 👤 User Flow
1. **Sign Up / Login**
2. **Choose a Yoga Pose**
3. **Start Real-Time Tracking** (AI detects pose accuracy)
4. **Stop & View Results**
5. **Track Progress & Compete on Leaderboard**

---

## 📊 Admin Flow
1. **Login as Admin**
2. **Manage Yoga Poses**
3. **View Leaderboard**
4. **Export Data (CSV)**
5. **Monitor Weekly/Monthly Analytics**

---

## 📁 Project Structure
```
📂 yoga-tracker/
│── 📂 static/         # Static assets (CSS, JS, Images)
│── 📂 templates/      # HTML Templates (User & Admin pages)
│── 📂 models/         # Database Models
│── 📂 routes/         # Flask Routes
│── 📂 utils/          # Utility functions (Pose Detection, Analytics)
│── app.py            # Main Flask Application
│── config.py         # Configurations
│── requirements.txt  # Required Python Packages
│── README.md         # Project Documentation
```

---

## 🔗 API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| `GET`  | `/` | Home Page |
| `GET`  | `/dashboard` | User Dashboard |
| `GET`  | `/pose_tracking/<pose_id>` | Start Pose Tracking |
| `GET`  | `/stop_asana/<usage_id>` | Stop Tracking |
| `GET`  | `/history` | View User Practice History |
| `GET`  | `/leaderboard` | User Leaderboard |
| `GET`  | `/admin_dashboard` | Admin Dashboard |
| `GET`  | `/admin_leaderboard` | Admin Leaderboard |
| `GET`  | `/export_leaderboard_csv` | Export CSV |

---

## 🤝 Contributing
Feel free to submit a **pull request** or open an **issue** to contribute to this project! 🚀

---

## 📜 License
MIT License - Free to use & modify.

---

## 📧 Contact
For any issues or suggestions, contact:  
📩 **maddy@makeskilled.com**  
🔗 **LinkedIn:** [Your Profile](https://linkedin.com/in/MadhuPIoT)  
🔗 **GitHub:** [Your GitHub](https://github.com/maddydevgits)
