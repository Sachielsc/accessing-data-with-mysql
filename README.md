# Access data via mysql

## CLI commands
### Log in to mysql
```bash
mysql -u root -p
```

### Run the app
If you use Maven, you can run the application by using `./mvnw spring-boot:run`. Alternatively, you can build the JAR file with `./mvnw clean package` and then run the JAR file, as follows:
```bash
java -jar target/gs-accessing-data-mysql-0.1.0.jar
```

### Add a person object and convert it to Xml
```bash
curl localhost:8080/demo/addAndConvertXml -d name=ThirdPerson2 -d email=someemail@someemailprovider.com
```

### View all person objects
- [Click here](http://localhost:8080/demo/all)

# Access data via jpa
## CLI commands
### Run the app
If you use Maven, you can run the application by using `./mvnw spring-boot:run`. Alternatively, you can build the JAR file with `./mvnw clean package` and then run the JAR file, as follows:
```bash
java -jar target/gs-accessing-data-jpa-0.1.0.jar
```

# My serialization demo

# TODO list
- gson
- jackson fastxml
- axiell
- compare
- recordset

# Reference sites
- [Accessing data with MySQL](https://spring.io/guides/gs/accessing-data-mysql/)
- [Accessing data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)
- [Jackson-conversions tutorial source code](https://github.com/eugenp/tutorials/tree/master/jackson-modules/jackson-conversions)
- [spring-data-jpa Example projects](https://spring.io/projects/spring-data-jpa#samples)