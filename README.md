# Midas
## Name: Sharmila P
## Reg no: 212224220094

#step-1

git clone https://github.com/<your-username>/forage-midas.git
cd forage-midas

#step-2
Recommended: IntelliJ IDEA (Community or Ultimate edition)

Make sure your IDE supports Spring Boot and Maven projects.

Configure the project to use Java 17:

Install JDK 17 on your system.

In IntelliJ: File -> Project Structure -> Project SDK -> Add JDK 17.
Project repo for the JPMC Advanced Software Engineering Forage program
```
<dependencies>
    <!-- Spring Boot JPA -->
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-data-jpa</artifactId>
        <version>3.2.5</version>
    </dependency>

    <!-- Spring Boot Web -->
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-web</artifactId>
        <version>3.2.5</version>
    </dependency>

    <!-- Spring Kafka -->
    <dependency>
        <groupId>org.springframework.kafka</groupId>
        <artifactId>spring-kafka</artifactId>
        <version>3.1.4</version>
    </dependency>

    <!-- H2 Database -->
    <dependency>
        <groupId>com.h2database</groupId>
        <artifactId>h2</artifactId>
        <version>2.2.224</version>
        <scope>runtime</scope>
    </dependency>

    <!-- Spring Boot Test -->
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-test</artifactId>
        <version>3.2.5</version>
        <scope>test</scope>
    </dependency>

    <!-- Spring Kafka Test -->
    <dependency>
        <groupId>org.springframework.kafka</groupId>
        <artifactId>spring-kafka-test</artifactId>
        <version>3.1.4</version>
        <scope>test</scope>
    </dependency>

    <!-- Testcontainers Kafka -->
    <dependency>
        <groupId>org.testcontainers</groupId>
        <artifactId>kafka</artifactId>
        <version>1.19.1</version>
        <scope>test</scope>
    </dependency>
</dependencies>
```

version ▼	Vulnerabilities	Repository	Usages	Date
3.30.x
3.30.0.CR1		Central	
0
Nov 12, 2025
3.29.x
3.29.2		Central	
33
Nov 08, 2025
3.29.1		Central	
32
Nov 05, 2025
3.29.0		Central	
38
Oct 22, 2025
3.29.0.CR1		Central	
33
Oct 15, 2025
3.28.x
3.28.5		Central	
35
Oct 22, 2025
3.28.4		Central	
36
Oct 16, 2025
3.28.3		Central	
38
Oct 09, 2025
3.28.2		Central	
37
Oct 01, 2025
3.28.1		Central	
37
Sep 24, 2025
3.28.0		Central	
36
Sep 17, 2025
3.28.0.CR1		Central	
32
Sep 10, 2025
3.27.x
3.27.1		Central	
0
Nov 12, 2025
3.27.0		Central	
42
Sep 17, 2025
3.27.0.CR1		Central	
32
Sep 09, 2025
3.26.x
3.26.4		Central	
34
Sep 17, 2025
3.26.3		Central	
41
Sep 09, 2025
3.26.2		Central	
38
Sep 03, 2025
3.26.1		Central	
37
Aug 29, 2025
3.26.0		Central	
37
Aug 20, 2025
#Step 3: Run the Tests

Locate TaskOneTests in src/test/java.
Run it in your IDE (right-click → Run TaskOneTests) or via Maven:
mvn test -Dtest=TaskOneTests
Wait for the tests to complete.



