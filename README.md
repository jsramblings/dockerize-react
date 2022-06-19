# Dockerize React

Repo for the step by step tutorial of Dockerizing a React app: https://jsramblings.com/dockerizing-a-react-app/

Build the Docker image:

```
docker build . -t dockerized-react
```

Run the image:

```
docker run -p 3000:80 -d dockerized-react
```
