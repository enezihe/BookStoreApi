# BookStoreApi




PC
    Bookstore-api.txt (Dev)
    Requrements.txt   (Dev)

    Dockerfile. (nbt)
    DockerCompose.yaml (nbt)
    
    Main.tf (nbt)                       Main.tf
                        Resource  github_repository
                                  github_branch_default
                                  github_repository_file

                                  aws_security_group
                                  aws_instance                    user-data (aws_intance)

                                                                  -install docker
                                                                  -install docker-compose
                                                                  -pull files from github
                                                                  -build image
                                                                  -docker compose up


