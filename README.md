# springboot-rabbitmq-producer-consumer

To start this application, we need to have rabbitmq server running.

I used docker to install and start rabbitmq server 
Command to install it:
docker pull rabbitmq:3.10-management
Command to start rabbitmq:
docker run --rm -it -p 15672:15672 -p 5672:5672 rabbitmq:3.10-management

We are forwarding the port to :5672
