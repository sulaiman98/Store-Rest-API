# Flask RESTAPI Project | Stores REST API

## Environment Requirements
- python v3.x
- Docker

## How to run this Project

### Clone the repo
```
git clone git@github.com:sulaiman98/flask-rest-apis-project.git
```
### Project Setup
- Create Virtual Environment
- Activate Virtual Environment
- Install Dependencies

```
pip install requirements.txt
```
### Create Docker Image
```
docker build -t [IMAGE NAME] .
```
### Run the Docker container Locally
```
docker run -dp 5005:5000 -w /app -v "$(pwd):/app" [IMAGE-NAME] sh -c "flask run --host 0.0.0.0"
```
[View Project Swagger UI here:](https://flask-rest-apis-project-qzce.onrender.com/swagger-ui)


