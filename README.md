# JavaGPT

<p align="center"> <img alt="Java Version" src="https://img.shields.io/badge/Java-17+-blue"> <img alt="License" src="https://img.shields.io/badge/License-MIT-green"> <img alt="Status" src="https://img.shields.io/badge/Version-1.0.0-brightgreen"> </p>

**JavaGPT** is an open-source project that provides an intelligent, HTTP-based educational assistant tailored for Java developers.  
Designed to enhance productivity and support learning, JavaGPT answers Java-related questions in real time — without relying on any third-party libraries.

---

## ✨ Features

- HTTP server built entirely with **pure Java** — no external dependencies.
- Covers Java SE, Java EE, Spring, Maven, Gradle, JUnit, Android, and more.
- Intelligent Q&A engine supporting core concepts like OOP, concurrency, collections, and streams.
- Designed for **maximum portability** and **zero setup**.
- Focused on promoting best practices, design patterns, and coding efficiency.

---

## 📂 Project Structure

```bash
java-gpt/
│
├── data/               # Java knowledge base (questions and answers)
├── docs/               # Project documentation
├── src/                # Source code
├── server/             # Lightweight HTTP server and routing
├── core/               # Core Q&A logic and response generation
├── build/              # Build scripts
├── LICENSE             # License file
└── README.md           # Project overview
```

---

## 🚀 Getting Started

### Prerequisites

- Java 17 or higher
- Git (optional)

### Installation (Standalone)

```text
Download the repository, unzip it, ensure Java 17+ is installed, and double-click `reboot.bat`.
```

### Git Installation

```bash
# Clone the repository
git clone https://github.com/PseuoDevelopment/java-gpt.git
cd java-gpt

# Compile the project
javac -d out $(find ./src -name "*.java")

# Run the server
java -cp out dev.javagpt.Main
```

---

## 🔥 Running the Server

By default, the server starts at `http://localhost:8080/`.  
Open any modern web browser and visit `http://localhost:8080/dashboard.html`.  
Log in using the default credentials:

```text
Username: admin
Password: password
```

You can also test the server directly using `curl`:

```bash
curl http://localhost:8080/q=What+is+a+class+in+Java
```

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for full details.

---

## 📅 Project Status

As of **April 28, 2025**:

- 100% **native Java** implementation (no third-party dependencies).
- HTTP server and core educational functionality are stable.
- Actively maintained and open to community contributions.

---

## 🔗 Useful Resources

- [Official Java SE Documentation](https://docs.oracle.com/en/java/)
- [Effective Java by Joshua Bloch](https://effectivejava.dev/)
- [Java Design Patterns](https://java-design-patterns.com/)
