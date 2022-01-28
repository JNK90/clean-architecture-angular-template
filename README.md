# Angular-Template (Angular v12)

This project shows a possible way to structure an angular app by [clean architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html) principles. Also it can be used as a template for new angular applications.

In addition this configuration uses [Jest](https://jestjs.io/) instead of jasmine for tests. Wich enables features like parallel execution of tests, generation coverage reports and removing a headless browser as dependency. 

Also this project includes 
* an example [Dockerfile](Dockerfile) for building and running an angular application in docker on an nginx server (including basic [nginx configuration](nginx/server.conf)).
* an example [Dockerfile](Dockerfile.sonar) for running tests and sending coverage reports to a SonarQube
* an example [Jenkinsfile](Jenkinsfile) including steps for SonarQube, buil the docker image and deploy it to a remote registry


## Possible Component-Frameworks:
* [Angular Material](https://material.angular.io/)
* [NG-Zorro](https://ng.ant.design/docs/introduce/en)
* [PrimeNG](https://www.primefaces.org/primeng/#/)

## Possible Stores (State Management)
* [Akita](https://github.com/datorama/akita) (recommendation)
* [NgRx](https://ngrx.io/)
