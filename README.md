# 🚀 DjangoStarter

**DjangoStarter** is a powerful template project for quickly starting work with the Django framework. It includes the essential configurations and structures needed for efficient development.

**English** | [Русский](README_RU.md) 

## 📚 About the Project

**DjangoStarter** provides a ready-made base structure for Django projects, allowing you to focus on developing your logic and functionality rather than setting up the initial project configuration.

### Features:

- 🔧 Convenient `settings.py` configuration with support for environment variables (`.env`).
- 🎨 Prepared structure for storing templates and static files.
- 📂 Modular organization of applications with easy URL management.
- 🔐 Basic security and configuration settings.

## 🏗️ Project Structure

```plaintext
DjangoStarter/
├── .env                # Environment variables (secret keys and configurations)
├── manage.py           # Script for project management
├── requirements.txt    # Project dependencies
├── static/             # Static files (CSS, JS, images)
├── templates/          # HTML templates
└── my_project/         # Main project module
    ├── settings.py     # Main Django settings
    ├── urls.py         # Main routing file
    ├── wsgi.py         # For deployment with WSGI servers
    └── apps/           # Project applications
```

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/Riffaells/DjangoStarter.git
cd DjangoStarter
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure environment variables

Create a `.env` file based on the example:

```bash
DEBUG=True
SECRET_KEY='your-secret-key'
DATABASE_NAME=db.sqlite3
```

### 4. Apply migrations and run the server

```bash
python manage.py migrate
python manage.py runserver
```

Open your browser and go to: [http://localhost:8000](http://localhost:8000)

## 🤝 Contributing

We welcome community contributions! Please create pull requests or open issues to improve the project.

## 📜 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more details.
