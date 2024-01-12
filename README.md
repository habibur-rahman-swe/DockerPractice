#  How to install docker
-   [Install WSL](https://learn.microsoft.com/en-us/windows/wsl/install)
-   [Docker installation GuideLine](https://docs.docker.com/desktop/install/windows-install/)

## Sampe - Docker Practice -1

###  Running  Docker for the first time
-   Create a docker file name `Dockerfile`
-   Configure the `Dockerfile`
    ```
    FROM node:alpine
    COPY . /app
    WORKDIR /app
    CMD node app.js
    ```

-   compile docker file using the command
    ```
    docker build -t docker-practice .
    ```

-   see the docker images using the command
    ```
    docker image ls
    ```

-   run in the docker using the command
    ```
    docker run "image-name"
    ```