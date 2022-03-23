# Create a JupyterLab environment for the EMG project

1. Install `docker` and `docker-compose`.
2. Copy your data in the `work/data` folder.
3. Run `./set_environment.sh` to prepare an `.env` file. It contains your UID and GID that will be used to make data transfer between the Jupyter environment and your host system seamless. You only need to do this once.
4. Summon the JupyterLab environment with `docker-compose up`.
5. Click on the link http://127.0.0.1:8888/lab?token=... that appears in the log.
6. Work in the work/notebooks folder within JupyterLab.
7. Shutdown the JupyterLab environment from the browser, or press `CTRL+C` in the terminal.
8. Clean up with `docker-compose down`.
