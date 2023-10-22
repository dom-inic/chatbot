## chatbot
Car Sales Chatbot enables users to interact with the chatbot for finding and purchasing cars.

##Features
- Real-time chat with the chatbot.
- Natural language understanding and processing.
- Search and browse a database of cars for sale.

## Installation

To run the Car Sales Chatbot locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/dom-inic/chatbot.git
cd chatbot
```

Install the project dependencies:
```bash
pip install -r requirements.txt
```
configure settings:
Set up Celery and Redis for background task processing.
Apply migrations:
```bash
python manage.py migrate
```
Start the development server:
```bash
python manage.py runserver
```
Run Celery for background tasks:
```bash
"celery -A config worker -l info"
```
Docker:
```bash
    docker-compose up --build
    docker compose up
```
