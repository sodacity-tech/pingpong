# pingpong

Basic REST API for testing with the Soda City Kubernetes cluster.

## Local Development

0. Clone this repo & `cd` to where you cloned it.

1. Create a Python virtual environment:

    ```sh
    python3 -m venv venv
    ```

2. Install the requirements into the virtual environment:

    ```sh
    venv/bin/python3 -m pip install -r requirements.txt
    ```

3. Spin up the API:

    ```sh
    venv/bin/fastapi dev main.py
    ```

    Access the API's docs from a browser at `localhost:8000/docs`.
