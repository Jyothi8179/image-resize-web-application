
### 📦 Build the Project
Run this command in the terminal:

```shell 
  mvn clean install
```

---

### 🐳 Setup Docker
#### 1. Check Docker Version
Ensure Docker is installed and running. Check the version with:
```shell
  docker --version
```

---

#### 2. Build Docker Image
To create a Docker image of your Spring Boot application, run:
``` shell
  docker build -t image-resize-app .
```

---

#### 3. Run Docker Container
Run the application container:
```shell
  docker run -p 8080:8080 image-resize-app
```

---

#### 4. Verify Running Containers
Check running containers with:
```shell
  docker ps
```

---

### 📚 Setup Docker Compose
#### 1. Build and Run All Containers
To build and run Spring Boot and MySQL together using docker-compose.yml:
```shell
  docker-compose up --build
```

---

#### 2. Check Docker Logs
To view logs from the application container:
```
docker logs image-resize-app
```

---

#### 3. Stop and Clean Containers
To stop the containers:
```shell
  docker-compose down
```

---

#### 4. Remove Docker Images and Containers
If you need to clean up Docker resources:
```
docker system prune -a
```

---


### 🚀 Start the applcation
- Go to the terminal and hit this command:
```shell
  mvn spring-boot:run
  ```



### 🚀 Access the Application
- Open your browser and navigate to:
```
http://localhost:8080
```
- Database is accessible at:
```
localhost:3307
```

---
