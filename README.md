# Frontend Eureka Client

The resulting docker image is a Eureka client that serves static files.

### Environment variables

|Variable   |Purpose   |Default   |
|---|---|---|
|EUREKA_URI   |Location of the Eureka Server   |http://localhost:8761/eureka   |
|PREFER_IP_ADDRESS   |Bound to eureka.instance.preferIpAddress property   |true   |
|SPRING_APPLICATION_NAME   |Bound to spring.application.name property   |frontend   |
|STATIC_LOCATION   |Location to find static files    |/files   |
|PORT   |Listening port   |80   |

### Notes

Error/ page not found is redirected to $STATIC_LOCATIONS/index.html
