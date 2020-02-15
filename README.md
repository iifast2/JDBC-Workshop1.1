READ ME . rmd 


# JDBC-Workshop1.1 CRUD + Mailing Service : Java Mail
JDBC Workshop 1.1  → CRUD JDBC ( Gestion : Apres Vente ) 
IT-Vision

### Velo 1.1 

# Velo ( Gest. Apres Vente )   #
 
used IDE : IntelliJ IDEA Community Edition
used DB : mysql ( workbench ) 

DBname : apres_vente

DB tables :

| personne/user↑ | appointement   | delivery    | reclamation   | repair   |
|----------------|----------------|-------------|---------------|----------|
| id             | idappointement | IdDelivery  | IdReclamation | IdRepair |
| nom            | date           | IdClient    | description   | IdBike   |
| prenom         | description    | IdBike      |               |          |
| age            |                | description |               |          |



user : Personne/deliveryman + → phoneNumber.

External Libraries : 

Javax.mail.jar

mysql-connector-java.8.0.19.jar

