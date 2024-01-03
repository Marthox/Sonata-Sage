# Sonata Sage

Hello and welcome to the Sonata Sage documentation. This is a work in progress and will be updated as we go along. But for now, here is a quick start guide to get you up and running.

## About
This project is divided into two sub projects. The first is the `sonata-sage-server` project which holds all the logic and backend development of Sonata Sage. The second one is the `sonata-sage-client` project which is the graphic user interface of project.

The server project is a Django project and is located in the `sonata-sage-server` sub-module.

The client project is a Svelte.js project and is located in the `sonata-sage-client` sub-module.

## Download the project
To download the project, you will need to clone the sub-modules as well. To do so, you can use the following command:

#### Using SSH (Recomended):
```bash
git clone --recurse-submodules git@github.com:MarthoxGJ/Sonata-Sage.git
```

#### Using HTTPS:
```bash
git clone --recurse-submodules https://github.com/MarthoxGJ/Sonata-Sage.git
```

## Run the project
You can run the project separately downloading each of the sub-modules and running them separately But you can also run them together using the `docker-compose.yml` file located in the root of the project. To do so, you will need to have Docker and Docker Compose installed on your machine. If you don't have them installed, you can follow the instructions on the [Docker website](https://www.docker.com/).

> [!NOTE]
> For more information on how to run each of the projects standalone you can refer to their respective repositories

Once you have Docker and Docker Compose installed, you can run the following command to start the project:

```bash
docker-compose up --build
```

If you only want to build it without running it, you can run the following command:

```bash
docker-compose build
```

After the project is built, you can run it using the following command:

```bash
docker-compose up
```
