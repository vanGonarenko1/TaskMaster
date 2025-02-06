# TaskMaster
TaskMaster is a lightweight task management app built with React and Django. It allows users to create, update, and delete tasks, helping them stay organized and boost productivity. The app features a clean UI, drag-and-drop task sorting, and a RESTful API for seamless data handling.
🔹 Key Features:
Task Management: Create, edit, and delete tasks.
Drag & Drop Sorting: Reorder tasks easily using a simple drag-and-drop feature.
Status Filtering: Filter tasks by pending, in progress, and completed.
Persistent Storage: Data is stored in a PostgreSQL database via Django REST API.
Authentication: Optional user authentication using Django.
🔧 Technologies Used:
Frontend:
React (UI Framework)
Tailwind CSS (Styling)
React DnD (Drag-and-drop functionality)
Backend:
Django & Django REST Framework (API & Database)
PostgreSQL (Database)
JWT Authentication (User authentication)
git clone https://github.com/your-username/TaskMaster.git
cd TaskMaster
cd backend
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
cd frontend
npm install
npm start
💡 Future Improvements:
Add due dates and reminders.
Enable collaborative tasks (teamwork).
Implement dark mode UI theme.
🏗️ Project Structure:
TaskMaster/
├── backend/ (Django API)
│   ├── manage.py
│   ├── tasks/ (Django App)
│   ├── db.sqlite3
│   ├── requirements.txt
├── frontend/ (React App)
│   ├── src/
│   │   ├── components/
│   │   ├── App.js
│   │   ├── index.js
│   ├── package.json
├── README.md
