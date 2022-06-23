# DEMO
* Step 1: Run RabbitMQ
```bash
# latest RabbitMQ 3.10
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.10-management
```
More details: [here](https://www.rabbitmq.com/download.html)

* Step 2: Run producer
```
go run send.go
```

* Step 3: Run consumer
```
go run receive.go
```

# Explanation
Refer: [here](https://www.rabbitmq.com/tutorials/tutorial-one-go.html)

