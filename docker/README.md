# Setup Docker

> This repository is based on `ROS-Noetic` 

## Build Docker Image
In current path, run the following command to build the docker Image with the name `industrial_grasp`.

```bash
bash build.bash
```

> **Note:**
> - You can change the name to whatever you like, just remember to update the new name in the [startup file](run_container.bash).

## Start Docker container
In current path, run the following command to start the docker container with the name `industrial_grasp_container`:
```bash
bash run_container.bash
```