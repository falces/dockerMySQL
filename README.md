# dockerMySQL
This project is a container to run in your local computer a MySQL database, version 9.1 and a PHPMyAdmin service to manage the database.
# Dependencies
You need Docker installed to run this project.
# Usage
Clone this project, open the created folder and clone the template.env file as .env, edit with your username and password.
Edit the ports in `docker-compose.yaml` file if you need.
Open a terminal and go into the folder, then run this command:
```bash
docker  compose  up  -d
```
It wil download and start a container MySQL and another container for PHPMyAdmin to manage the database.
## Connections
(If you have changed the ports, use yours)
- MySQL: localhost:3306
- PHPMyAdmin: http://localhost:8080/