#### Config Server
```bash
docker build -f deployment/Dockerfile --build-arg SERVICE_NAME=infra/config-server -t shop-microservices-config-server:latest .
```

#### Eureka Server
```bash
docker build -f deployment/Dockerfile --build-arg SERVICE_NAME=infra/eureka-server -t shop-microservices-eureka-server:latest .
```

#### Admin Server
```bash
docker build -f deployment/Dockerfile --build-arg SERVICE_NAME=infra/admin-server -t shop-microservices-admin-server:latest .
```

#### API Gateway
```bash
docker build -f deployment/Dockerfile --build-arg SERVICE_NAME=infra/api-gateway -t shop-microservices-api-gateway:latest .
```

#### Auth Service
```bash
docker build -f deployment/Dockerfile --build-arg SERVICE_NAME=infra/auth-service -t shop-microservices-auth-service:latest .
```

#### Product Service
```bash
docker build -f deployment/Dockerfile --build-arg SERVICE_NAME=service/product-service -t shop-microservices-product-service:latest .
```

#### Customer Service
```bash
docker build -f deployment/Dockerfile --build-arg SERVICE_NAME=service/customer-service -t shop-microservices-customer-service:latest .
```

#### Order Service
```bash
docker build -f deployment/Dockerfile --build-arg SERVICE_NAME=service/order-service -t shop-microservices-order-service:latest .
```
