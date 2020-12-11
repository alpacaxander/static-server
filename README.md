# Static Server

The resulting docker image serves static files.

### Environment variables

|Variable   |Purpose   |Default   |
|---|---|---|
|SPRING_APPLICATION_NAME   |Bound to spring.application.name property   |frontend   |
|STATIC_LOCATION   |Location to find static files    |/files   |
|PORT   |Listening port   |80   |

### Notes

Error/ page not found is redirected to $STATIC_LOCATIONS/index.html
