# Spring Cloud - MSA Example


## Service Discovery
- Service Discovery 역할을 하는 localhost에서 port 8761을 활용해 Eureka 서버를 활성화 한다.

- 각 User Service 서버를 활성화하고 Eureka 서버를 등록한다. 이때, 각 port 는 0으로 설정하고 로드 밸런서 처리를 위해 instance-id 값을 할당한다. 
