# similarity-ml
Building model that can compute similarity score between two images

## Quick Start Instructions

### Prerequisites

1. Django Project for the microservices admin
2. Microservices with individual databases

### Tools and Resources

There are two ways to set up, one is to use [docker](https://www.docker.com/products/docker-desktop/) and the other is to set up locally. For local set up, you
will need the following

1. [Python 3.8+](https://www.python.org/downloads/release/python-387/)
2. Virtualenv. Optional but preferred, see steps below.

### Prerequisite for Docker users
   Start container
   ```shell
   docker compose up -d
   docker compose exec vm bash
   ```

### Installation
1. Upgrade pip
    ```shell
    pip install --upgrade pip
    ```
2. Install Virtualenv
    ```shell
    pip install virtualenv
    ```
3. Create and start virtual environment
    ```shell
    virtualenv venv
    source venv/bin/activae
    ```
4. Install with python requirements
    ``` shell
    pip install -r requirements.txt
    ```

### Run
After starting the containers as stated above in the **_Prerequisite for Docker users_**, Start jupyter Server
```shell
jupyter notebook --ip 0.0.0.0 --no-browser --allow-root
```