# Alpine Jenkins

This is a fully functional Jenkins server which runs in an alpine linux that is ready out of the box to build pipelines and comes with the blue ocean plugin.

## Supported Tags
* latest


## Basic Usage
`docker run -p 8080:8080 liatrio/jenkins-alpine`

## Docker Enabled Usage  
To allow Jenkins to utilize your host Docker installation for spinning up containers in builds and building images, mount the Docker socket as a volume.

`docker run -p 8080:8080 -v /var/run/docker.sock:/var/run/docker.sock liatrio/jenkins-alpine`

jenkin orcal vm key:
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQCPtqs2Qhb2pkISWuJq0S274smd9/UUeFhX2A/zzdXJq07UTpYzBhzchVqzUJVhtyguZOs5w8Q9pDl134uBp4Wfp2oHV3CI6eNbIMhlZDEF1SyGMFD1sQugyVJzCT7L2GLKoM92CZmFkuoDABh1IKefakxL+SLmc8SuLWnYmE5OY7dFd6/DHTox8DjHHXxYkr/JabnW9dWGK4XaxpTDu0cgmpUNNG+gixvfKoH2m/vioDYb8iGZs+hYxL1FzY5Fh82/N/TaKPmXJg+yXqGISOvUY0Ynr+4iR4JrUO8G1bMRoZeqnTunBlmwp0PyiH47RCz/JbfN+9q3zkH5LbQjQlj1gzC1dVLl3AxZozC2Coi9XjJIq0VfBl8QPM9WAFlmlijQboAvphBdWzqWjsqa3ATUcQ9PpGiN8YwtsfzIWRZORwuRwTKuw7YHXEPJRBBC3zuc8m0Ng4ddq9pBOKbQPSC/y/4VJe2kss0Fj5uSWI10umbXAwlY8G3bo4KbVr7IMuM= root@jenkins-master
