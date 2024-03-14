# Cucumber in Spring Boot using Dependency Injection

This code sample shows how to use Dependency Injection in Cucumber within a Spring Boot application.

You can find the complete instructions on this post at The Practical Developer site: [Cucumber Tests with Dependency Injection using Spring Boot](https://thepracticaldeveloper.com/cucumber-tests-spring-boot-dependency-injection//)

![Cucumber and Dependency Injection in a Spring Boot App - The Practical Developer](images/cucumber-spring-boot.png)



### TestScenarios 
Feature: Bag functionalities

Scenario: Putting one thing in the bag
Given the bag is empty
When I put 1 potato in the bag
Then the bag should contain only 1 potato

Scenario: Putting few things in the bag
Given the bag is empty
When I put 1 potato in the bag
And I put 2 cucumber in the bag
Then the bag should contain 1 potato
And the bag should contain 2 cucumber