# CONTRIBUTING

## How to run the DockerFile locally

""""
docker run -dp 5005:5000 -w /app -v "$(pwd):/app" [IMAGE-NAME] sh -c "flask run --host 0.0.0.0"

"""