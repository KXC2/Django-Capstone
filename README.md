# Django-Capstone
Like a Phoenix
📝 Overview
This Django web application is a fun and thoughtful space that allows users to explore:

1. Phoenix’s diary entries

2. Puns(Programming Puns)

3. A showcase of weird but insightful thoughts

Simple. Honest. Chaotic — just like Phoenix.

🚀 Features
View Phoenix Diary Entries
Peek into the everyday life of a Phoenix.

Puns
Chuckle and groan your way through witty humor.

Weird Thoughts
Dive into the strange and curious mind of Phoenix.

⚙️ Getting Started
📦 Prerequisites
Make sure you have the following installed:

Python 3.8+

pip

virtualenv

Docker (optional, for containerized setup)

🛠️ Installation & Configuration (Local Development)

1. Clone the repository
git clone https://github.com/KXC2/Django-Capstone
cd Like_a_Phoenix

3. Set up a virtual environment
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate

4. Install dependencies
pip install -r requirements.txt

5. Apply migrations
python manage.py migrate

6. Run the development server
bash
Copy
Edit
python manage.py runserver
Then visit: http://127.0.0.1:8000

🐳 Running with Docker
If you prefer using Docker, follow these steps:

1. Build the Docker image
docker build -t Like_a_Phoenix .

2. Run the container
docker run -p 8000:8000 Like_a_Phoenix
Or if using Docker Compose (optional if you have a docker-compose.yml):
docker-compose up --build
Then visit: http://localhost:8000

🙌 Author
Lebogang "Phoenix" Mosopa

_"You can call me Phoenix"_
