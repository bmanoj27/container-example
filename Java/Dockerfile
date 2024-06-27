FROM openjdk:latest  
COPY . /var/www/java  
WORKDIR /var/www/java  
RUN javac Hello.java  
CMD ["sh", "-c", "java Hello && while true; do sleep 1000; done"]
