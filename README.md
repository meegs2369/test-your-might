## Service-point
This library contains useful interfaces and classes to help do some boilerplate type tasks that I find myself doing repeatedly.

* Palindrome - using the Stream api determine if a word is a palindrome.
* RandomStringGenerator - using the Stream api generate a random alpha numericString
* SingletonCollector - collect 1 from a stream of objects based on predicate.
* ListToMap - given a String and a delimiter, use stream to build map.
* MapToString - given a map of Strings return a string of all values.
* LayoutProvider - provides a way to mask Logs for sensitive data.
* JpaHibernateEntityManagerHelper - creates a LocalContainerEntityManagerFactoryBean 
preconfigured to use JPA and hibernate.
* DatabaseConnectionStrings - provides PostgreSQL and MSSQL database connection url
Strings.
* DataHelper - creates DataSource for application.
* WebGetter - performs a GET on a given url and returns a string.

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=meegs2369_service-point&metric=alert_status)](https://sonarcloud.io/dashboard?id=meegs2369_service-point)