# <div style="display:flex; align-items:center; gap:10px"><img src="https://jupyter.org/assets/homepage/main-logo.svg" alt="drawing" style="width:130px; padding-top: 10px"/><span>Notebook Practises</span></div>

*This repository is only for personal practise purpose* 😝

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
