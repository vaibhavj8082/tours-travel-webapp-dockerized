
# 🧳 Tours and Travel WebApp (Dockerized)

#### 📝 Overview

This is my personal project — a Tours and Travel website built using HTML, CSS, and JavaScript.
The project is containerized using Docker, allowing it to run seamlessly across different environments with minimal setup.

It’s a static web application designed to showcase clean UI, smooth navigation, and Docker deployment skills.


#### 🚀 Features

🌍 Responsive and attractive design

🧭 Explore travel destinations and packages

💬 Contact section for inquiries

🐳 Deployed using Docker container

⚙️ Portable and lightweight setup





### 🐳Docker Deployment Steps

Clone The Repository

```bash
git clone https://github.com/vaibhavj8082/tours-travel-webapp-dockerized.git
cd tours-travel-webapp-dockerized
```

Build the Docker Image

```bash
docker build -t tours-travel-webapp .
```

Run the Container
```bash
docker run -d -p 8080:80 tours-travel-webapp
```

Then visit 👉http://localhost:8080 to see the site live.



