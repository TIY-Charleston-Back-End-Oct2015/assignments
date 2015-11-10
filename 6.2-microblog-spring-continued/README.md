# Microblog Continued

![screenshot](screenshot.png)

## Description

Use Spring Data to store the microblog messages in PostgreSQL. Add editing functionality as well.

## Requirements

* In your `build.gradle`, add the following to your dependencies:
  * `compile('org.springframework.boot:spring-boot-starter-data-jpa')`
* Open the Gradle sidebar and click the refresh button
* In PostgreSQL, create a database for your project called `microblog`
* Add the necessary lines to `application.properties`
* Modify the `Message` class to mark it as a Spring Data entity and make it store an `Integer id` with the proper annotations so it is treated as an id and is automatically generated
* Create an interface that extends `CrudRepository<Message, Integer>`
* In your controller, add the repository with `@Autowired` and use it instead of the `ArrayList<Message>`
* Add a way to edit messages and use the repository to update the object
