# 🌤️ Weather Website using Django

A simple web application that allows users to check the current weather conditions of any city using real-time data from the OpenWeatherMap API. This project is built using Python and the Django framework.

---

## 📌 Features

- Search for weather by city name
- Displays temperature, humidity, wind speed, and weather description
- Real-time data using the OpenWeatherMap API
- Clean, responsive user interface using HTML/CSS
- Error handling for invalid city names

---

## ⚙️ Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS (Bootstrap optional)
- **API**: OpenWeatherMap

---

## 🚀 Getting Started

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/saugatpoudel100/Weather.git
cd Weather
```

### 2. Create a Virtual Environment

```bash
python -m venv env
```

### 3. Activate the Virtual Environment

- Windows:
  ```bash
  env\Scripts\activate
  ```

- macOS/Linux:
  ```bash
  source env/bin/activate
  ```

### 4. Install Dependencies

```bash
pip install django 
```

### 5. Create Django Project & App (if not already)

```bash
django-admin startproject weatherproject
cd weatherproject
python manage.py startapp weatherapp
```

### 6. Add App to Settings

Add `'weatherapp'` to the `INSTALLED_APPS` list in `settings.py`.

---

## 🔑 API Setup

1. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api).
2. Store it securely in `settings.py` or a `.env` file:

```python
OPENWEATHERMAP_API_KEY = 'your_api_key_here'
```

---

## 🛠️ Useful Django & Python Commands

| Command | Description |
|--------|-------------|
| `django-admin startproject <name>` | Create a new Django project |
| `python manage.py startapp <name>` | Create a new Django app |
| `python manage.py makemigrations` | Create migrations for DB changes |
| `python manage.py migrate` | Apply migrations to the DB |
| `python manage.py runserver` | Run the development server |
| `python manage.py createsuperuser` | Create an admin user |
| `pip install django requests` | Install dependencies |
| `python -m venv env` | Create virtual environment |
| `source env/bin/activate` | Activate virtual environment (Linux/macOS) |
| `env\Scripts\activate` | Activate virtual environment (Windows) |

---

## 🌍 How to Run the Project

```bash
python manage.py runserver
```

Then visit: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 🧠 Future Improvements

- 5-day weather forecast
- City search suggestions
- Toggle between Celsius and Fahrenheit
- Improved mobile UI
- Save previous search history



---

## 🙋‍♂️ Contact

Have questions or suggestions? Reach out via [sauggupoudel10@gmail.com].
