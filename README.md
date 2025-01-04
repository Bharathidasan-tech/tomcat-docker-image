# Tomcat Docker Image
Apache Tomcat Docker Image form alpine scratch. It's multi docker image.

. Tomcat Image - Apache Tomcat 10.1.31
. Alpine Linux - Alpine Minirootfs 3.20.0-x86_64
. JDK17

### Development environment setup

Follow the steps to bring up the development environment in your local and build Docker Image.

1) Install Git, Maven and Docker</br>
2) Clone the Develop branch using "git clone [https://github.com/Bharathidasan-tech/microservices-e-commerce-sample.git](https://github.com/Bharathidasan-tech/tomcat-docker-image/tree/develop)" </br>
3) Docker build command "docker build -t <image-name>:<version> -f <Docker-file-name> ."</br>


# Example To build Image
docker build -t tomcat-base-image:openjdk17 -f Dockerfile.from-scratch .
