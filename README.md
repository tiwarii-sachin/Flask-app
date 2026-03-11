\# Flask Docker Kubernetes App



This is a simple Flask web application containerized using Docker

and deployed using Kubernetes.



\## Technologies Used

\- Python

\- Flask

\- Docker

\- Kubernetes

\- GitHub



\## Run with Docker



docker build -t flask-app .

docker run -p 5000:5000 flask-app



Open in browser:

http://localhost:5000



\## Run with Kubernetes



kubectl apply -f deployment.yml

kubectl apply -f service.yml



Check services:

kubectl get svc

