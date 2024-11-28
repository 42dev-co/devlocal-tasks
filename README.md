# devlocal-tasks
This is to create a development local env with minikube

## TL;DR

1. Make sure you have devkit installed. [Install devkit.](https://github.com/42dev-co/devkit)

2. Install Devlocal module
    ```
    devkit install_mod url=https://github.com/42dev-co/devlocal-tasks
    ```
3. Start a new cluster project 
    ```
    devkit devlocal:init name=<project name>
    ```

4. Make changes to `setup.config`

5. Install requirements, `task install-requirements`

6. Create/Start cluster, `task up`.


