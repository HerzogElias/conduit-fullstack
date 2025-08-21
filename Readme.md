# Conduit Fullstack Project

## Table of Contents
1. [Introduction](#Introduction)
2. [Prerequisites](#Prerequisites)
3. [Quickstart](#Quickstart)
4. [Usage](#Usage)
   - [Description Fullstack Project](#Description-Fullstack-Project)
   - [Stop Docker Container](#Stop-Docker-Container)
   - [Delete Docker Container](#Delete-Docker-Container)

## Introduction
This is a Readme Description of our Conduit Project.The Conduit is a Clone of <a href=https://medium.com/>Medium.com<a>

## Prerequisites
- Docker 
- Docker Compose 

## Quickstart
1. Clone the following Git Repository: 
```bash
git clone git@github.com:HerzogElias/conduit-fullstack.git
```


2. Navigate to the Correct Direcotry: 
```bash
cd conduit-fullstack
```

3. Clone all Submodules 
```bash
git submodule update --init --recursive
```

4. Copy your Backend Environement file.
Naviagte: 
```bash
cd backend
```

Copy the File: 
```bash
cp example.env .env
```

Navigate Back to Root: 
```bash
cd ..
```

5. Start Docker Compose 
```bash
docker compose up --build
```

## Usage 
### Description Fullstack Project 
This is a Fullstack Web Application with Github Submodules. 
Here you can see, the Root Github Repository. 

To Change to Frontend or Backend use the Links: 
- <a href="https://github.com/HerzogElias/conduit-frontend/">Frontend</a>
- <a href="https://github.com/HerzogElias/conduit-backend/">Backend</a>

### Stop Docker Container 
To Stop the Container use the following Command: 
```bash
docker compose down 
```
### Delete Docker Container 
To Deleate the Docker Container inklusive all Networks and Volumes use the following Command: 
```bash
docker compose down -v
```