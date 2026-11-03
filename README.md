# Ch22 – Hibernate Extended Model

Educational project (Coding Factory, AUEB): extends the Teacher–Course model with **one-to-one**, **one-to-many**, **many-to-many** relationships and **enums**, using JPA / Hibernate on MySQL.

**Technologies:** Java 21 · Maven · JPA / Hibernate · MySQL · Lombok

This project focuses on the entity mapping. Starting the application is enough for Hibernate to generate the tables from the entities (`hbm2ddl.auto = update`); no sample data or queries are included.

JPQL, Criteria Queries, fetch strategies and the `EntityManager` lifecycle are covered in the [previous project (simple Teacher–Course model)](https://github.com/giwtasta20/hiber10-pro).

> The password in `persistence.xml` belongs to my local database (educational use only).

Theory notes: [NOTES.md](NOTES.md)