# Java & Angular Full-Stack Development Container 🚀

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E9432E?style=for-the-badge&logo=ubuntu&logoColor=white)

This repository provides a professional, isolated, and standardized development environment using **Docker**, **WSL2**, and **VS Code Dev Containers**. 

By using this setup, you ensure that the entire development stack is identical across any machine (Windows, Linux, or macOS), eliminating the "it works on my machine" problem.

## 🛠 Technologies Included

- **Java:** 17 (OpenJDK Bookworm)
- **Node.js:** 20.x
- **Angular CLI:** Latest Stable
- **Base OS:** Debian Bookworm (via Microsoft Dev Container Images)
- **Pre-installed Extensions:**
  - Extension Pack for Java
  - Angular Language Service
  - Prettier
  - Thunder Client (for API testing)

## 🏗️ Prerequisites

Before you begin, ensure you have the following installed:

1.  **Docker Desktop** (with WSL2 backend enabled for Windows users).
2.  **Visual Studio Code**.
3.  **Dev Containers Extension** (from Microsoft).

## 🚀 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/YOUR_USERNAME/java-angular-devcontainer.git
    ```
2.  **Open the folder in VS Code.**
3.  When prompted by the pop-up in the bottom right corner, click **"Reopen in Container"**.
    - *Alternatively: Press `Ctrl+Shift+P`, type `Dev Containers: Rebuild and Reopen in Container`.*
4.  Wait for the container to build. Once finished, you will have a terminal ready with Java, Node, and Angular.

## 📂 Project Structure

- `.devcontainer/`
  - `Dockerfile`: Instructions to build the environment.
  - `devcontainer.json`: VS Code automation and tool configuration.
- `workspace/`: (Optional) Your source code for Spring Boot and Angular projects.

## 📝 Environment Variables

The environment comes pre-configured with:
- `JAVA_OPTS`: Optimized memory limits for JVM.
- `NG_CLI_ANALYTICS`: Disabled by default for better terminal experience.
- `NODE_OPTIONS`: Memory limits for large Angular builds.

---
Developed by Renata Freitas - [[LinkedIn](https://www.linkedin.com/in/reafreitas1/)]
