<h2>Digital Innovation: Expert class - Development of unit tests to validate a beer inventory management REST API.</h2>

REST API for managing beer stocks. Unit tests were developed to validate the beer inventory management system, and also presented the main concepts and advantages of creating unit tests with JUnit and Mockito. In addition, the development of our API's functionalities was carried out through the practice of TDD.


The following topics were addressed:

* Download a project through Git to develop our unit tests.
* Conceptual presentation on tests: the test types pyramid, and also the importance of each test type during the development cycle.
* Focus on unit tests: show why it is important to develop these types of tests as part of the software development cycle.
* Main frameworks for unit testing in Java: JUnit, Mockito and Hamcrest.
* Development of unit tests for validation of basic functionalities: creation, listing, query by name and exclusion of beers.
* TDD: presentation and practical example on 2 important features: increase and decrease in the number of beers in stock.

To run the project in the terminal, type the following command:

```shell script
mvn spring-boot:run
```

To run the test suite developed during live coding, simply run the following command:

```shell script
mvn clean test
```
After executing the above command, just open the following address and view the project execution:

```
http://localhost:8080/api/v1/beers
```

The following prerequisites are necessary for the execution of the project developed during the class:
* Java 14 or higher versions.
* Maven 3.6.3 or higher versions.
* Intellj IDEA Community Edition or your favorite IDE.
* GIT version control installed on your machine.
* A lot of desire to learn and share knowledge :)


Below are useful links: 

* [SDKMan!for managing and installing Java and Maven](https://sdkman.io/)
* [Intellij IDEA Community Reference, downloadable](https://www.jetbrains.com/idea/download)
* [Intellij Command Shortcut Palette](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
* [Spring's official website](https://spring.io/)
* [JUnit 5 official website](https://junit.org/junit5/docs/current/user-guide/)
* [Mockito official website](https://site.mockito.org/)
* [Official Hamcrest website](http://hamcrest.org/JavaHamcrest/)
* [References - testing in general with Spring Boot](https://www.baeldung.com/spring-boot-testing)
* [Reference to the REST architectural pattern](https://restfulapi.net/)
* [Test Pyramid Reference - Martin Fowler](https://martinfowler.com/articles/practical-test-pyramid.html#TheImportanceOftestAutomation)

[ This link](https://drive.google.com/file/d/1KPh19mvyKirorOI-UsEYHKkmZpet3Ks6/view?usp=sharing), following the slides presented as the script used for the development of the project of our session.


