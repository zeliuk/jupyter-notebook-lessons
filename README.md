# ![Jupyter](https://jupyter.org/assets/logos/rectanglelogo-greytext-orangebody-greymoons.svg) <br>Notebook Practices

*This repository is only for personal practices purpose* 😝

### ⚙️ Prerequisites

- Docker must be installed on your system.

### 🚀 How to Run Jupyter Notebook with Docker

1. Pull the Jupyter base image:

    ```bash
    docker pull jupyter/base-notebook
    ```

2. Run the container and mount your current directory:

    ```bash
    docker run -p 8888:8888 -v "$PWD":/home/jovyan/work jupyter/base-notebook
    ```
