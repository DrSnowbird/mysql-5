# MySQL

* MySQL 5 Server

# Configuration
The docker container assumes there is a default <some_path>/workspace folder to map to the container's internal /workspace folder. 

The default, './run.sh', will use/create the local folder, "$HOME/data_docker/mysql-5/workspace" to map into the docker's internal "/workspace" folder.

The above approach will ensure all your projects created in the container's "/workspace" folder is "persistent" in your local folder, i.e., "$HOME/data_docker/mysql-5/workspace"


# Build (if you want build your local docker image instead of pulling from openkbs/atom-java-mvn-python3)
```
./build.sh
```

# Run
```
./run.sh
```
