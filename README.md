# Docker Projects Repository

Welcome to the Docker Projects Repository.
This repository serves as a centralized place for storing various Dockerfiles and Docker Compose projects.

## Introduction

This repository contains a collection of Dockerfiles and Docker Compose files for different projects.
Each project is organized into its own directory with all the necessary files to build and run the Docker containers.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- Docker
- Docker Compose

### Usage

To use any of the Docker projects in this repository, follow these steps:

1. Clone the repository:

```shell
git clone https://github.com/oURMIo/dockers.git
cd dockers
```

2. Navigate to the project directory you are interested in.

3. Navigate to the chosen project's folder and use either:

```shell
docker build -t myapp:latest .
```

or, depending on the chosen project:

```shell
docker-compose up -d
```
