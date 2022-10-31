# doc

./mvnw install

docker build -t demov1 . 

docker run demov1:latest -dt -p 8000:8080 

http://localhost:8080/actuator
