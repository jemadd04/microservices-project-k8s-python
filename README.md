# Microservice Learning Project

Following a code along from FreeCodeCamp to learn more about microservice architecture and system design.

Technologies/concepts covered:
- Kubernetes
- Python
- MySQL
- RabbitMQ
- MongoDB
- Auth flow
- API Gateway
- JWTs

Last left off:
2/13/24 8:14pm
53:00 minute mark: https://www.youtube.com/watch?v=hmkF77F9TLw&list=FLLZ6bn8l9DrejakOcKLhOXQ&index=8&t=297s
We created the auth service and routes; next we are creating the infrastructure code to deploy the service into Kubernetes

In the terminal cd to: /system_design/python/src/auth

Common commands:
python3 server.py - to run the server file
mysql -uroot - to connect to mysql
mysql -uroot < init.sql - to drop the sql configuration into mysql
mysql -uroot -e "DROP DATABASE auth" - to drop the database if a change is needed in init.sql
mysql -uroot -e "DROP USER auth_user@localhost" - to drop the auth user if a change is needed in init.sql