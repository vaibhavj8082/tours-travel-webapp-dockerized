🧳 Tours and Travel WebApp (Dockerized)

This is a Tours and Travel website built using HTML, CSS, and JavaScript, designed to provide a modern and responsive user interface for travel booking and tour management.
The project is containerized using Docker, allowing easy deployment and consistent performance across environments.

🐳 Docker Setup and Deployment
Clone the Repository
git clone https://github.com/vaibhavj8082/tours-travel-webapp-dockerized.git
cd tours-travel-webapp-dockerized

Build Docker Image
docker build -t tours-travel-webapp .

Run Container
docker run -d -p 8080:80 tours-travel-webapp

Now open your browser and visit 
http://localhost:8080
