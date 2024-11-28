# devlocal-tasks
This is to create a development local env with minikube

## TL;DR

1. Make sure you have devkit installed. [Install devkit.](https://github.com/42dev-co/devkit)

2. You also need to install Docker, as different machines (e.g., Windows, Mac, or Linux) have varying configurations. This is a prerequisite.

3. Install Devlocal module
    ```
    devkit install_mod url=https://github.com/42dev-co/devlocal-tasks
    ```
4. Start a new cluster project 
    ```
    devkit devlocal:init name=<project name>
    ```

5. Make changes to `setup.config`

6. Install requirements, `task install-requirements`

7. Create/Start cluster, `task up`.


