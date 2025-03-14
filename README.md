# Dockerized MySQL Utility Scripts

## Motivation

Docker is awesome! However, working with MySQL in a Dockerized environment can involve complex commands with many options and arguments. These utility scripts simplify the process by providing easy-to-use commands for common MySQL tasks.

**Note**: These scripts use the official MySQL Docker image available at [MySQL Docker Hub](https://registry.hub.docker.com/_/mysql/).

---

## Commands Provided

### 1. `dmysql-server`
Starts a new MySQL Server instance.

### 2. `dmysql`
Opens the MySQL CLI.

### 3. `dmysql-create-database`
Creates a new database.

### 4. `dmysql-import-database`
Imports a database into the MySQL Server.

dmysql-server (Start a new MySQL Server)
dmysql (Open the mysql cli)
dmysql-create-database (Creates a new database)
dmysql-import-database (Imports a database)
---

## Installation

$ cd directory_with_scripts
$ sudo chmod +x dmysql*
$ sudo cp dmysql* /usr/local/bin
