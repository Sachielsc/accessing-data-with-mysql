# My Spring data Jpa demo

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

# My serialization demo

# Reference sites
- [Accessing data with MySQL](https://spring.io/guides/gs/accessing-data-mysql/)
- [Jackson-conversions tutorial source code](https://github.com/eugenp/tutorials/tree/master/jackson-modules/jackson-conversions)