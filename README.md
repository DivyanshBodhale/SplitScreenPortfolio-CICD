# SplitScreenPortfolio


🚀Built a fully automated CI/CD pipeline where every GitHub commit triggers Jenkins to build, push, and deploy Dockerized applications automatically using Docker Compose.


I designed and implemented an end-to-end CI/CD pipeline that fully automates application build, packaging, and deployment using Jenkins, GitHub, Docker, and Docker Compose.

🔄 How the pipeline works:

Any code change or Jenkinsfile update pushed to GitHub triggers Jenkins automatically via GitHub Webhook.

Jenkins runs the pipeline on a dedicated agent, ensuring scalable and isolated execution.

The latest code is pulled from the GitHub repository, followed by a test stage to validate code quality.

A Docker image is built using a Dockerfile, securely tagged, and pushed to Docker Hub using Jenkins-managed credentials.

The application is then deployed automatically using Docker Compose, pulling the latest image and restarting containers in detached mode.

🧩 Key DevOps Concepts Implemented:

Pipeline as Code using Jenkinsfile stored in GitHub

Webhook-based CI/CD triggering

Secure credential management in Jenkins

Docker image lifecycle automation (build → tag → push)

Continuous Deployment using Docker Compose

📌 Impact:

Eliminated manual deployments

Ensured consistent, repeatable builds

Enabled faster and safer application releases

Tech Stack: Jenkins | GitHub | Docker | Docker Hub | Docker Compose | Linux | CI/CD |
