# Minimal Actix Web Server (Rust)

This project is a simple web server built with **Rust** using the [Actix Web](https://actix.rs/) framework.  
It starts a server at [`http://localhost:8080`](http://localhost:8080) and returns the string `"kn"` when you access the root endpoint (`/`).

---

## 📂 Repository Overview
This repository demonstrates:
- Setting up and running an HTTP server with Actix Web.
- Defining a basic route (`GET /`).
- Returning a plain text response.

You can use this as a starting point for building REST APIs or web applications with Rust.

---

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Run the server
```bash
cargo run
```

### 3. Test the endpoint
```bash
curl http://localhost:8080
```

---

# 🛠️ Tech Stack
- *Rust*
- *Actix Web*
