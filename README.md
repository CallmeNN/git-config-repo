Config-server for movie-booking app application reads properties for movie-service from this file. 

Furthermore Eureka-server assists in the service registry and discovery and allows to easily communicate with another service, simply by knowing the service name and not having to worry about the address details. So we have used service 
name like USER-SERVICE and THEATRE-SERVICE and eureka automaticatlly discovers their uri for us. In the image below we can see all the instances registered on eureka and can be discovered

![image](https://github.com/user-attachments/assets/79f7c922-66b8-4cfc-875d-983946ab3fd8)
