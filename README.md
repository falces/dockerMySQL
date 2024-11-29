# dockerMySQL

dockerMySQL is a container to run in your local computer a MySQL database, version 9.1 and a PHPMyAdmin service to manage the database.

# Dependencies

You need Docker installed to run this project.

# Usage

Clone this project, open the created folder and edit the template.env file with your username and password, then rename it from `template.env` to `.env`.

Open a terminal and go into the folder, then run this command:

```bash
docker compose up -d
```

It wil download and start a container MySQL and another container for PHPMyAdmin to manage the database.

## Connections

- MySQL: localhost:3306
- PHPMyAdmin: http://localhost:8080/
