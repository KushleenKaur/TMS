Part c: Transaction Management Using Spring and Hibernate
Objective:
To create a banking system using Spring integrated with Hibernate that allows users to transfer money between accounts while ensuring transaction consistency.

Explanation:
This task focuses on:

Spring transaction management (@Transactional).
Integrating Hibernate to handle persistence.
Steps involved:

Create two entities: Account and Transaction.

Use Spring annotations to:

Configure services and DAOs.
Annotate service methods with @Transactional.
In the service layer, write logic to:

Deduct money from one account.
Add money to another account.
Ensure that if any step fails, the transaction rolls back, maintaining atomicity and consistency.

This task demonstrates:

Real-world transactional use cases.
Declarative transaction handling in Spring.
Integration of Spring's service layer with Hibernate's persistence layer.

