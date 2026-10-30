# Lab 5 - CST8915 Full-stack Cloud-native Development: Containerizing the Algonquin Pet Store with Docker

## Demo:
[https://youtu.be/xQ4YVV4k9-Q](https://youtu.be/xQ4YVV4k9-Q)

## Docker Hub images:
- **Order Service** : [https://hub.docker.com/r/bou0167/order-service](https://hub.docker.com/r/bou0167/order-service)
- **Product Service** : [https://hub.docker.com/r/bou0167/product-service](https://hub.docker.com/r/bou0167/product-service)
- **Store Front** : [https://hub.docker.com/r/bou0167/store-front](https://hub.docker.com/r/bou0167/store-front)

## Service repositories:
- **Order Service**: [https://github.com/bout0167/order-service-L4](https://github.com/bout0167/order-service-L4)
- **Product Service (Python)**: [https://github.com/bout0167/product-service-python-L4](https://github.com/bout0167/product-service-python-L4)
- **Store Front**: [https://github.com/bout0167/store-front-L4](https://github.com/bout0167/store-front-L4)

## Store Front API Host Configuration
The Store Front Docker image uses the following API URLs:
- Order Service: [http://localhost:3000](http://localhost:3000)
- Product Service: [http://localhost:3030](http://localhost:3030)

The embedded API host is localhost.