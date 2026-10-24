# 📰 [Project Name — NewsApp]

## ✨ Features

### 🔐 Authentication System
- ✅ User registration
- ✅ Secure login & logout
- ✅ Password change functionality
- ✅ Protected routes with `@login_required`

### 📝 News Management
- ✅ Create new articles
- ✅ Upload featured images for each article
- ✅ Edit and delete articles
- ✅ Display articles in a clean, organized list

### 🎨 User Interface
- ✅ Modern, minimal, and creative design
- ✅ Fully responsive across all devices
- ✅ Smooth and engaging UX
- ✅ Custom fonts and iconography

### ⚙️ Infrastructure
- ✅ Clean and scalable architecture
- ✅ Class-Based Views
- ✅ Secure forms with CSRF protection
- ✅ Media file handling

---



1.Create and activate a virtual environment:
# Linux / macOS
python3 -m venv .venv
source .venv/bin/activate

# Windows
python -m venv .venv
.venv\Scripts\activate

2.Install dependencies:
pip install -r requirements.txt

3.Apply migrations:
python manage.py makemigrations
python manage.py migrate

4.Create a superuser:
python manage.py createsuperuser

5. Run the development server:
python manage.py runserver

Then open your browser at http://127.0.0.1:8000 🎉
