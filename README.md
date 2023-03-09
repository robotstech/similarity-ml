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
2. Virtualenv. Optional but preferred

### Installation

1. Install with python requirements
    ``` shell
     pip install -r requirements.txt
    ```

### Run

- #### using docker
   Start containers 
   ```shell
   docker compose up
   ```

- #### without docker
   Start jupyter Server
   ```shell
   jupyter
   ```