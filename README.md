### **Node.js Docker Application Overview**

This is a simple Node.js application containerized using Docker. The application responds with **"Hello, Docker with Node.js!"** when accessed at the root URL (`/`). It is designed for quick deployment inside a Docker container, ensuring seamless environment consistency.

---

### 🐳 **Docker Image Features:**

* **Base Image:** `node:18` – the official Node.js runtime.
* **Express Server:** Simple web server running on port `3000`.
* **Dockerized:** Fast, portable, and ready for production or local development.

---

### 🚀 **Docker Commands**

1. **Pull the Docker image (if hosted on DockerHub):**

   ```bash
   docker pull sudheshna998/node-docker-app
   ```

2. **Build the Docker image:**

   ```bash
   docker build -t node-docker-app .
   ```

3. **Run the Docker container:**

   ```bash
   docker run -d -p 3000:3000 node-docker-app
   ```

4. **Access the application:**
   Open your browser and navigate to:

   ```
   http://localhost:3000
   ```

   You should see the message: **Hello, Docker!**

Dockerhub:


Github:
