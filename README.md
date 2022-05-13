# Traefik Docker Scaffold

### **Description**

This will create a dockerized stack for a Laravel/Lumen application, consisted of the following containers:
-  **traefik-proxy**, your reverse proxy and load balancer for microservices.

### **Setup instructions**

**Prerequisites:**

* Depending on your OS, the appropriate version of Docker Community Edition has to be installed on your machine.  ([Download Docker Community Edition](https://hub.docker.com/search/?type=edition&offering=community))

**Installation steps:**

1. Create a new directory in which your OS user has full read/write access and clone this repository inside.

2. Open a new terminal/CMD, navigate to this repository root (where `docker-compose.yml` exists) and execute the following command:

    ```
    $ docker-compose up -d
    ```

   This will download/build all the required images and start the stack containers. It usually takes a bit of time, so grab a cup of coffee.

3. After the whole stack is up, your traefik proxy will be ready
