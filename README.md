# 🐳 Docker Container Lifecycle Lab

A hands-on Docker lab focused on understanding the complete **Docker Container Lifecycle**, from creating and managing containers to building a custom Docker image using `docker commit`.

This project was completed as part of the **Containers with Docker** module in the DevOps Engineer Diploma.

---

## 📖 Overview

This lab demonstrates the fundamental Docker operations required to manage containers throughout their lifecycle.

The exercises include:

- Creating containers
- Starting and stopping containers
- Executing commands inside containers
- Inspecting container information
- Removing containers
- Force deleting running containers
- Creating a custom Docker image from a running container
- Verifying the generated image

---

## 🎯 Lab Objectives

- Understand the Docker container lifecycle.
- Practice common Docker CLI commands.
- Learn how to inspect container metadata.
- Execute commands inside running containers.
- Build a reusable Docker image using `docker commit`.

---

## 📁 Repository Structure

```text
docker-container-lifecycle-lab/
│
├── README.md
├── LICENSE
│
├── screenshots/
│   ├── 01-container-creation-and-start.png
│   └── 02-container-management-and-inspection.png
│
├── commands/
│   └── docker-commands.md
│
└── docs/
    └── Lab01-Manage-container.pdf
```

---

## 🛠️ Technologies Used

- Docker
- Ubuntu 22.04
- NGINX
- Alpine Linux

---

## 🚀 Lab Workflow

The following tasks were completed during this lab:

### Step 1 — Create Containers

- Create an **NGINX** container named `web-server`
- Create an **Alpine** container named `linux-tester`

---

### Step 2 — Start Containers

Start both containers and verify that they are running successfully.

---

### Step 3 — Execute Commands

Inside the containers:

- Display running NGINX processes
- Create a new directory
- Create a file inside the container

---

### Step 4 — Inspect Containers

Inspect both containers and verify:

- Container ID
- Image
- Status

---

### Step 5 — Stop Containers

Gracefully stop both containers.

---

### Step 6 — Delete Containers

Remove the stopped container.

---

### Step 7 — Force Delete Running Container

Delete a running container using the force option.

---

### Custom Docker Image

Create a custom Docker image from a running Ubuntu container using:

- Ubuntu 22.04
- Package installation
- Custom files
- Docker Commit
- Image verification

---

# 📸 Screenshots

## Container Creation and Startup

<img width="1777" height="498" alt="2-container-management-and-inspection" src="https://github.com/user-attachments/assets/9fe051aa-dbc9-463f-b4c9-3c020c82b61b" />


---

## Container Management and Inspection

<img width="1777" height="498" alt="2-container-management-and-inspection" src="https://github.com/user-attachments/assets/fba1c665-9081-442e-82aa-f5d38d3bbe52" />


---

## 📚 Documentation

The original lab document can be found inside the **docs** directory.

```
docs/Lab01-Manage-container.pdf
```

---

## 📄 Commands Reference

All Docker commands used during this lab are available in:

```
commands/docker-commands.md
```

---

## 📌 Skills Gained

- Docker CLI
- Container Lifecycle
- Docker Images
- Container Inspection
- Process Management
- Interactive Containers
- Docker Commit
- Image Creation
- Linux Containers

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Mohamed Mosad**

DevOps Engineer | Cloud & Infrastructure Enthusiast

- GitHub: https://github.com/Mohamed-Mosad-98
- LinkedIn: https://www.linkedin.com/in/mohamed-mosad-516aa717b/
