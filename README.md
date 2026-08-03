# Containerized Tetris Application

A lightweight, classic Tetris game built on HTML5 Canvas and JavaScript, packaged inside a production-ready Nginx Docker container. 

This repository was updated and modified as part of a hands-on **Project** with [NextWork](https://nextwork.ai).


## Quick Start with Docker

### Option 1: Run Prebuilt Image from Docker Hub (Recommended)

Run the container directly using the published Docker Hub image:

```sh
docker run -d -p 8080:80 --name tetris alinpsw/tetris-app:v2.0
```

---

### Option 2: Build & Run Locally from Scratch

1. **Clone the repository:**

```sh
git clone [https://github.com/shafiswapnil/tetris.git](https://github.com/shafiswapnil/tetris.git)
cd tetris
```

2. **Build the Docker image:**

```sh
docker build -t my-tetris .
```

3. **Run the container:**

```sh
docker run -d -p 8080:80 --name my-tetris-app my-tetris
```

---

## Links & Resources

* 🐳 **Docker Hub Registry:** [alinpsw/tetris-app](https://hub.docker.com/r/alinpsw/tetris-app)
* 💻 **GitHub Repository:** [shafiswapnil/tetris](https://github.com/shafiswapnil/tetris)
* 📖 **Project Documentation:** [NextWork Documentation](https://nextwork.ai/zealous_orange_zesty_pummelo/docs/4384806b-4801-48a4-9763-c056c53e57aa)
* 🏷️ **Original Upstream Repository:** [bsord/tetris](https://github.com/bsord/tetris)

---

## 📄 License

This project is open-source and licensed under the [MIT License](LICENSE)

