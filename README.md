# Tomcat Docker Base Image
Apache Tomcat Docker Image (Alpine + JDK17)

A lightweight, production-ready Docker image for running Apache Tomcat 10.1.31, built on Alpine Linux Minirootfs (3.20.0-x86_64) with OpenJDK 17.

This image is designed for minimal size, faster startup, and cloud-native deployments.

# Features

Multi-stage build for optimized image size

Apache Tomcat 10.1.31 pre-configured

OpenJDK 17 runtime

Based on Alpine scratch (3.20.0-x86_64)

Minimal and secure footprint

### Development environment setup

Follow the steps to bring up the development environment in your local and build Docker Image.

1) Install Git, Maven and Docker</br>
2) Clone the Develop branch using "git clone <this-repo>" </br>
3) Docker build command "docker build -t <image-name>:<version> -f <Docker-file-name> ."</br>


# Example To build Image
docker build -t custom-tomcat-base-image:openjdk17 -f Dockerfile.from-scratch .
