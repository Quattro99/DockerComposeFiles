# UniFi Network Application with MongoDB - Docker Compose Setup

This Docker Compose configuration file sets up the UniFi Network Application along with a MongoDB instance. It includes the necessary initialization scripts and configurations to run these services seamlessly.

## Author
- Michele Blum

## Overview

The `mongodb-and-unifinetworkapplication.yml` file defines two services:
1. **unifi-db**: A MongoDB container utilized by the UniFi Network Application.
2. **unifi-network-application**: The UniFi Network Application that relies on the MongoDB service.

### MongoDB Initialization Script
- Creates necessary databases and users for the UniFi Network Application.

## Source
- [UniFi Network Application Docker Configuration](https://github.com/linuxserver/docker-unifi-network-application)

## Prerequisites
- Docker and Docker Compose installed on your system.
- An existing Docker network.

## Usage

1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-repo/docker-unifi-mongodb.git
   cd docker-unifi-mongodb

## Note
- Replace all placeholder paths (`/PATH/unifi-db` and `/PATH/unifi-network-application`) with the actual paths on your system in the `mongodb-and-unifinetworkapplication.yml` file.