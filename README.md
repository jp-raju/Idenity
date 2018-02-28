# Idenity


Instructions:

clone from: https://github.com/jp-raju/Idenity

run as maven spring project: mvn spring-boot:run

IDE : Import as existing maven project

Request Example:

Method: GET

Url: http://localhost:8080/api/scan (configured by default to 8080)

NOTE:

User can specifcy using query paramater with the name path. 

EXAMPLE: 

http://localhost:8080/api/scan?path=http://localhost:8080/api/scan?path=D:\\Data\\gitrepos\\qa\\automated_testing\\target\\allure-results

(Please escape backslashes in the specificed path like the example above)
