# Capmotion
Prueba capmotion
Se creó un archivo comprimido en zip para mayor velocidad de descarga.
Para instalar descomprimir el zip e importarlo en Springboot application.
En application.properties colocar las siguientes lineas: 

"spring.h2.console.enabled=true
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.username=sa
spring.datasource.password=123
spring.jpa.database-platform=org.hibernate.dialect.H2Dialect
spring.datasource.driverClassName=org.h2.Driver"

La bd es la que se encuentra en la linea 8, por favor cambiar la url y colocar la url de donde tengas tu bd, para ello creala desde 
la consola de h2 una nueva bd vacía, que ya de por si el programa al ejecutarse en springboot va a crear las tablas necesarias.

