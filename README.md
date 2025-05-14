# Python Hello World Web Project

This is a minimal Python web project using Flask that displays "Hola Mundo" in the browser. It is containerized using Docker and is ready for deployment on Railway with GitHub integration.

---

##  Docker Usage

### Build Docker Image
Run the following command in the root of the project directory:

```bash
docker build -t kevineduardo14/hello-world-python .
```

### Run the Docker Container

```bash
docker run -p 5000:5000 kevineduardo14/hello-world-python
```

### Login to Docker Hub

```bash
docker login
```

---

### Push the Image to Docker Hub

```bash
docker push kevineduardo14/hello-world-python
```

---

### Pull the Image from Docker Hub

```bash
docker pull kevineduardo14/hello-world-python
```

---

### DockerHub Repository

[https://hub.docker.com/r/kevineduardo14/hello-world-python](https://hub.docker.com/r/kevineduardo14/helloworldpython)

---

## 🚀 Deployment on Railway

1. Go to [https://railway.app](https://railway.app)
2. Log in with GitHub
3. Create a new project and **deploy from your GitHub repository**
4. Railway will detect the Dockerfile and deploy automatically
5. Activate **Auto Deploy** so changes to the repository are redeployed automatically

---

## ✅ Live Deployment

After deployment, Railway will provide a public URL:

```

```

Access it to see your "Hola Mundo" in the browser.
