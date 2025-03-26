# 🔄 Dependency Injection in Python with FastAPI

A simple demonstration of dependency injection patterns using FastAPI in Python. This project showcases how to implement and use dependency injection in a FastAPI application.

## 🎯 Overview

This project demonstrates:
- Basic FastAPI setup
- Dependency injection using FastAPI's `Depends`
- Type annotations with `Annotated`
- Simple HTTP GET endpoint implementation

## 🛠️ Installation

1. Clone the repository:
```sh
git clone https://github.com/tamerakdeniz/Dependency-Injection-Python.git
cd Dependency-Injection-Python
```

2. Install dependencies:
```sh
pip install -r requirements.txt
```

## 🚀 Usage

1. Start the FastAPI server:
```sh
uvicorn main:app --reload
```

2. Visit `http://localhost:8000/hello` in your browser or use curl:
```sh
curl http://localhost:8000/hello
```

## 📚 API Endpoints

- `GET /hello`: Returns a hello world message using dependency injection
- Visit `http://localhost:8000/docs` for the interactive API documentation

## 🔧 Dependencies

- Python 3.13
- FastAPI 0.112.2
- Uvicorn 0.23.2

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
