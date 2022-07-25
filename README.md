# CDE-MFPE-Project-Audit-Management-System

## Authors :

<table>
    <tr>
        <td>
            <a href="https://github.com/Chandu-A-B">Chandu A B</a>
        </td>
        <td>
            <a href="https://github.com/NIks3s">Nikunj Baid</a>
        </td>
        <td>
            <a href="https://github.com/Navyachowdary9908">Nelluri Navyasree</a>
        </td>
    </tr>
</table>

# INTCDE22IJ087-POD1-AUDIT-MANAGEMENT
MFPE Project

# AUDIT-MANAGEMENT Application

This is a full-stack MFPE project built as part of Cognizant CDE internship.

Following services are part of the application:

## Frontend:
* Audit management Portal

## Backend:
* Authorization Microservice
* Audit Checklist Microservice
* Audit Benchmark Microservice
* Audit Severity Microservice


## Requirements
* Java 11
* Angular 12

## Setup

Launch the above mentioned 7 microservices in your IDE. Import the project as `Maven Project` and wait for the dependencies to install. If any port is unavailable in your machine you can change the port for the respective microservice in the `application.properties` file under `Backend/microservice/src/main/resources/application.properties`

After the 7 microservices are up and running launch the ClaimApp angular application using `ng serve`

## Usage

### Initial Launch

On initial launch of application the user is prompted with a home page of the application. In the navigation bar user can click the `Login` button for authentication.


### Login Portal

User has to enter his username and password to login. Following credentials can be used to login:

|  Username  |  Password  | 
|------------|------------|
|  nikunj    |  nikunj12  |
|  chandu    |  chandu12  |
|  navya     |  navya12   |


## Logged In

Authenticated users can now access the features of the application from the navigation bar under their username.

