Birder
======

Birder is a convinient clone of Twitter.

## Setup

1. Clone the repository

```bash
git clone https://github.com/aibike20/Birder.git
```

2. Create the `.env` file specifying the database 
   and web server configuration parameters.

```bash
# Inside .env file...

# Database Configurations
BIRDER_DB_HOST=
BIRDER_DB_PORT=
BIRDER_DB_NAME=
BIRDER_DB_USER=
BIRDER_DB_PASSWORD=
BIRDER_DB_DIALECT= # one of 'mysql' | 'mariadb' | 'postgres' | 'mssql'

# Web Server Configurations
BIRDER_PORT=

# Web App Configuration
BIRDER_ADMIN_LOGIN=
BIRDER_ADMIN_PASSWORD=
BIRDER_SESSION-SECRET=
BIRDER_PASSWORD_SALT_ROUNDS=
```

2. Istall all the dependencies.

```bash
npm install
```

3. Start the server.

```bash
node index.js
```

## Credits

Zarylbekova Gulsunai <zarylbekovagulsunai@gmail.com>