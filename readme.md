# Calculator

- [Calculator](#calculator)
  - [Dependancies](#dependancies)
  - [Running the app](#running-the-app)
    - [running from cli](#running-from-cli)
    - [running docker](#running-docker)
    - [stopping docker](#stopping-docker)
    - [push to docker hub](#push-to-docker-hub)
  - [Usage](#usage)
    - [Authenticating](#authenticating)
    - [Adding](#adding)
      - [Setting the token](#setting-the-token)
      - [Copying the token](#copying-the-token)
      - [Setting body](#setting-body)
      - [Sending the request](#sending-the-request)
    - [Evidence](#evidence)
      - [Application Image in DockerHub](#application-image-in-dockerhub)
      - [Application running in Docker](#application-running-in-docker)

github: https://github.com/Kushan-Nilanga/calculator

## Dependancies
1. Docker
2. Nodejs
3. Npm

## Running the app
### running from cli
npm start 

### running docker
docker-compose up --build -d

### stopping docker
docker-compose down

### push to docker hub
docker build -t calculator .
docker tag calculator:latest dknathalage/calculator:latest
docker push dknathalage/calculator:latest

https://hub.docker.com/r/dknathalage/calculator

## Usage

### Authenticating

![picture 1](./images/d0f0cb5f8299c46eb1d184c824c4008610f40ac6b992546c979fb8de7466e958.png)  

### Adding

#### Setting the token
![picture 2](./images/2ecb5cd949896f7f1a3951c6bef71b24e11d115bc1d45ea7eb44515739938d49.png)  

#### Copying the token
![picture 3](./images/38f64827014496c8562562f0eea300ab15cbcc47a902b3d1dda54455a799a561.png)  

#### Setting body
![picture 4](./images/c6ddb632a870c88ffe5f703fa7a9f46e09144e70f57adf21c831034fc90cf1b2.png)  

#### Sending the request
![picture 5](./images/8728c920c44a63fcd2654276f99c34262219b1ef31c4e2e8062d6f803c35f371.png)  

### Evidence

#### Application Image in DockerHub
![picture 1](images/a9cd76b4f8d8f04e90af76e5e40e59e75d02833ff393f7919f05405c6e9ebedd.png)  

#### Application running in Docker
![picture 2](images/385bdc6d2e382aa55e72455631d148932c7baace302ebeabb8b0998b455e0e3f.png)  





