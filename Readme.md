https://howtodoinjava.com/spring/spring-cloud/microservices-monitoring/

three applications for the following purposes
1. Eureka server: the main serve which maintains the service registry of all the other microservices
2. Api-gateway: the main api gateway
3. Employee-service: a microservice which deals with employee realted business logic

below are some endpoints to test
 - run the employee service
  eg: http://localhost:8011/findEmployeeDetails/111

 - run the api gateway
  eg: http://localhost:8010/employeeDetails/111
 - live stream the api gateway
  eg: http://localhost:8010/hystrix
 - and enter the below url in the first input field, leave rest two fields as blank
  eg: http://localhost:8010/hystrix.stream
 - run the eureka serve
  eg: http://localhost:8761
 - watch the other micro service health status
  eg: http://localhost:8761/admin
