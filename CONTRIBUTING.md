#CONTRIBUTING

## RUN DOCKER LOCALLY

```
docker run -v ${PWD}:/app -p 8000:5000 -i --rm --name flsk flask-api

docker run -dp 5000:5000 -w /app -v "$(PWD):/app" IMAGE NAME sh -c "flask-run"

```