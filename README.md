# 🚀 DevOpsify: My DevOps Projects Portfolio

Welcome! I'm **Pratik Wayal**, and this is my DevOps portfolio – a hands-on showcase of my experience with Docker, CI/CD, Jenkins, AWS, reverse proxies, custom domain deployments, and more.

---

## 🛠️ Technologies & Tools

| Tool / Platform     | Usage                                   |
|---------------------|------------------------------------------|
| **Docker**          | Containerizing applications              |
| **GitHub Actions**  | CI/CD pipelines                          |
| **Jenkins**         | Automated jobs and pipelines             |
| **AWS EC2**         | Cloud hosting (Navidrome, custom apps)   |
| **Nginx / Apache**  | Reverse proxy, SSL config                |
| **Certbot (Let's Encrypt)** | HTTPS and SSL setup            |
| **DockerHub**       | Hosting and pulling images               |
| **Render**          | Auto-deployment from GitHub              |
| **DNS Management**  | Custom domain and A-records              |

---

## 📦 Featured Projects

## 🔹 1. To-Do Web App with CI/CD (React + Docker + GitHub Actions + Render)

A simple yet production-ready To-Do Web App built with React, containerized using Docker, and deployed via **GitHub Actions CI/CD** to **Render**. This project demonstrates a complete DevOps workflow from source to deployment.

### 🔧 Tech Stack
- React (Frontend)
- Docker & DockerHub (Containerization)
- GitHub Actions (CI/CD Pipeline)
- Render (Deployment)

### 🚀 Live Demo
🌐 [View Deployed App](https://my-todo-app-latest.onrender.com/)  
📦 [Docker Image on DockerHub](https://hub.docker.com/repository/docker/pratikw123/my-todo-app)

### 📸 Screenshots

| Description                     | Screenshot |
|---------------------------------|------------|
| ✅ Final Web App UI (Deployed)   | ![To-Do App Demo](./screenshots/to_do_app_Demo.png) |
| 🔁 GitHub Actions CI/CD Build   | ![CI Build](./screenshots/github_action_build_to_do.png) |
| 🔄 Render Deployment Log        | ![Render Logs](./screenshots/pull_build_to_do_app_render.png) |
| 📦 DockerHub Image              | ![DockerHub Repo](./screenshots/docker_hub_to_do.png) |

---

### 🔹 [2. Image Forgery Detection (FYP)](./image-forgery-detection/)

- **Stack**: Node.js + Flask | Single Dockerfile | Render
- Dockerized frontend + backend into a single service (no docker-compose)

<details>
  <summary>📸 Proof Screenshots</summary>

  ![Dockerized Node+Flask](./screenshots/image-forgery-docker.png)
  ![Render Deployment](./screenshots/image-forgery-render.png)

</details>

---

### 🔹 [3. Navidrome Music Server on AWS](./navidrome-aws-deploy/)

- **Stack**: Docker | AWS EC2 | Nginx | Certbot | Custom Domain
- Self-hosted media server with HTTPS and DNS configured at [https://music.forge-detect.me](https://music.forge-detect.me)

<details>
  <summary>📸 Proof Screenshots</summary>

  ![EC2 Running](./screenshots/navidrome-ec2.png)
  ![Nginx Reverse Proxy](./screenshots/nginx-config.png)
  ![HTTPS Certificate](./screenshots/certbot-success.png)

</details>

---

### 🔹 [4. Jenkins Docker Automation](./jenkins-docker-automation/)

- **Stack**: Jenkins | Docker | Nginx
- Jenkins job to pull code → build Docker image → run container → reverse proxy with Nginx

<details>
  <summary>📸 Proof Screenshots</summary>

  ![Jenkins Dashboard](./screenshots/jenkins-job.png)
  ![Docker Container Running](./screenshots/jenkins-docker-container.png)

</details>

---

## 💡 Why This Portfolio?

I’m passionate about building real-world systems using DevOps tools. Each of these projects helped me deeply understand containerization, automation, deployment, and infrastructure management.

---

## 📫 Let's Connect!

- 💼 [LinkedIn](https://www.linkedin.com/in/pratikwayal/)
- 💻 [GitHub](https://github.com/pratikwayal01)
- 🌐 [Website](https://forge-detect.me) *(if available)*

---

⭐ **Star this repo** if you found it interesting or helpful!
