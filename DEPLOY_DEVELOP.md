| ENVIRONMENT | MEANING | DEVELOPMENT | PRODUCTION |
|-------------|---------|-------------|------------|
| Fetch API URL | URL where client makes requests using fetchi API | localhost name. eg: http://localhost:5000 | DEPLOYED_WEBSITE_NAME. eg: https://rfr-21-dashboard.herokuapp.com/
| DB config | Configuration details such as username, database name, host and password that are required to connect to an online database | locally hosted db config values. eg: host:localhost | online hosted db config values. eg: host: "ec2-54-78-127-245.eu-west-1.compute.amazonaws.com"
| Port | Port on which server is served | local port. eg: 5000 | process.env.PORT