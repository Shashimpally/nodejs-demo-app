# 🚀 CI/CD Pipeline with GitHub Actions and Docker

This project shows how to set up a simple *CI/CD (Continuous Integration and Deployment) pipeline* using *GitHub Actions*. It is designed to automatically build, test, and push a Docker image of a Node.js app whenever code is pushed to the main branch.

---

## 📌 What This Project Does

When you push code to the main branch:
1. ✅ Pulls the latest code from GitHub
2. 🔧 Installs Node.js and project dependencies
3. 🧪 Runs tests using npm test
4. 🐳 Builds a Docker image of your app
5. 📤 Pushes the Docker image to your DockerHub account

---

## 🔧 Tools & Technologies Used

- *GitHub Actions* – for automation
- *Node.js* – backend runtime environment
- *Docker* – for containerizing the app
- *DockerHub* – for storing the Docker image
- *GitHub Secrets* – for securely storing login credentials

---

## 🛠 Files Included

- .github/workflows/ci-cd.yml – Workflow file for GitHub Actions
- Dockerfile – Instructions to build the Docker image
- package.json – Contains project dependencies and scripts
- README.md – Project explanation (this file)

(Add any screenshots here if required)

---

## 🔐 GitHub Secrets Setup

To allow DockerHub login, you need to add the following secrets in your GitHub repository:

- USERNAME → Your DockerHub username  
- PASSWORD → Your DockerHub password or access token

---

## ✅ How to Use

1. Fork or clone this repository
2. Add your Dockerfile and update package.json as needed
3. Add the required secrets in GitHub
4. Push code to the main branch
5. GitHub Actions will run the pipeline automatically

---

## 📦 Output

At the end of the pipeline:
- The app is tested and packaged into a Docker image
- The image is pushed to your DockerHub account and ready to use

---

## 📍 Note

You can later extend this to deploy your image to services like:
- AWS, GCP, or Azure

---

Made with 💻 using GitHub Actions + Docker
