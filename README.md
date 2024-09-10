# Docker-Postgres
## Deploying Postgres into Ec2 instance using Docker compose
### Steps using my git repo :
- Step 1: Clone the repo(git clone https://github.com/sainithin761000/docker-postgres-installation.git)
- Step 2: Creates a directory named docker-postgres-installation. Navigate into it.(cd docker-postgres-installation)
- Step 3: open the docker-compose.yaml file and give the user, database name and password.(vi docker-compose.yaml)
- Step 4: Run the docker-compose.yaml file 
          (docker-compose up -d)
- Step 5: (docker ps -a) verify the container 

Note: Download and install docker-compose(if not installed)
- (sudo curl -L “https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose)
- (sudo chmod +x /usr/local/bin/docker-compose)
- (docker-compose --version) for verification
