# spingbootwithdocker

docker build --tag springboot-docker . 
docker run -dp 8085:8083 --name springboot-docker-container -v "$(pwd):/app" springboot-docker


server.port=8083
#spring.datasource.url=jdbc:mysql://mysql-springboot-container:3306/StudentManagement
#spring.datasource.username=root
#spring.datasource.password=Abc@123456789
#spring.jpa.hibernate.naming.physical-strategy=org.hibernate.boot.model.naming.PhysicalNamingStrategyStandardImpl
#spring.datasource.driver-class-name =com.mysql.cj.jdbc.Driver
#spring.jpa.show-sql=true
#spring.jpa.hibernate.ddl-auto=update
