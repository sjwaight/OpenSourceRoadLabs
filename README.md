# Open Source Roadshow Labs
A collection of links to various labs that can be used to demonstrate how Microsoft Azure can easily support Open Source solutions.

If you wish to add something or find something out-of-date or that doesn't work. Submit a PR or raise an Issue.

> **Important note:** Many labs / exercises recommend trying the Azure Cloud Shell as a first step. While it is possible to do many of the labs listed with the Cloud Shell, you will find that there are certain steps that don't work or that you need to change. It may be worthwhile creating a Linux Virtual Machine on which you can run these labs instead if you are unfamiliar with Linux-based development.

## Development and Hosting Options

[Section overview presentation (PDF)](presentations/01-Overview-and-hosting-options.pdf)

* [Azure Serverless: Customer Car Reviews Sample](https://github.com/Azure-Samples/customer-car-reviews)
* [Linux App Service: Docker Images](https://github.com/azure-app-service/apps)
* [Linx App Service: Magneto + MySQL](https://github.com/Azure-App-Service/apps/tree/master/Magneto)
* [Node.js + MongoDB](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-tutorial-nodejs-mongodb-app)
* [PHP (Laravel) + MySQL](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-tutorial-php-mysql) - [notes](PHP-Laravel+MySQL.md) :thumbsup:
* [Python + PostgreSQL](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-tutorial-docker-python-postgresql-app)
* [Create Node.js App](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-get-started-nodejs)
* [Create Java App](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-get-started-java)
* [Build an Azure Function using Java](https://docs.microsoft.com/en-gb/azure/azure-functions/functions-create-first-java-maven)
* [Create PHP App](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-get-started-php)
* [Create Python App](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-get-started-python)
* [Build Java API in Azure App Service](https://docs.microsoft.com/en-au/azure/app-service-api/app-service-api-java-api-app)
* [Build a Node.js RESTful API](https://docs.microsoft.com/en-au/azure/app-service-api/app-service-api-nodejs-api-app) - *Important Note* - [notes](Node.js-RESTful-API.md) :thumbsup:
* [Deploy Java 8 Spring Boot API to Azure App Service](https://blogs.msdn.microsoft.com/cloud_solution_architect/2016/11/23/deploy-java-8-spring-boot-api-to-azure-app-service/)
* [Java Coffee Shop](https://github.com/Azure-Samples/app-service-web-java-get-started) - [notes](Java-Coffee-Shop.md) :thumbsup:
* [Advanced: Java App - Scale an App](https://github.com/Azure-Samples/app-service-java-scale-web-apps-on-linux)
* [Manage Azure websites with Ruby](https://github.com/Azure-Samples/app-service-web-ruby-manage)
* [Python Flask app on Azure App Service Web](https://github.com/Azure-Samples/python-docs-hello-world)
* [Python sample for Azure App Service - Django](https://github.com/Azure-Samples/app-service-web-python-get-started)
* [PHP sample for Azure App Service - CodeIgniter](https://github.com/Azure-Samples/app-service-web-php-get-started)
* [Web application development with Node.js and Express using DocumentDB](https://github.com/sjwaight/documentdb-node-todo-app) - [notes](node-express-docdb.md) :thumbsup: 
* [App Service Mobile completed quickstart for Node.js backend](https://github.com/Azure-Samples/app-service-mobile-nodejs-backend-quickstart)
* [Using Python with Visual Studio Code](https://github.com/Microsoft/TechnicalCommunityContent/tree/master/Open%20Dev%20Framework/Python/Session%202%20-%20Hands%20On)
* [Java on Service Fabric](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-create-your-first-linux-application-with-java)
* [Java Reliable Actors (Service Fabric)](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-reliable-actors-get-started-java)
* [Java Reliable Services (Service Fabric)](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-reliable-services-quick-start-java)
* [Advanced: Python Contoso Ads App (Cloud Services)](https://github.com/Azure-Samples/cloud-services-python-contoso-ads-application)
* Advanced: Traffic Manager with App Service - pick one of the other labs and deploy it behind [Traffic Manager](https://docs.microsoft.com/en-us/azure/traffic-manager/).
* [App service CDN](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-tutorial-content-delivery-network)
* [Azure App Service Architecture (3): App Service on Linux](http://itnerd.space/2016/11/02/azure-app-service-architecture-3-app-service-on-linux/)
* [.Net Core web app on App Service on Linux](https://docs.microsoft.com/en-gb/azure/app-service/containers/quickstart-dotnetcore)

## Datastores

[Section overview presentation (PDF)](presentations/02-Datastores.pdf)

* [MySQL in 10 minutes on Azure](https://blog.siliconvalve.com/2017/06/30/zero-to-mysql-in-less-than-10-minutes-with-azure-database-for-mysql-and-azure-web-apps/)
* [Python + PostgreSQL](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-tutorial-docker-python-postgresql-app)
* [Design a PostresSQL Database](https://docs.microsoft.com/en-us/azure/postgresql/tutorial-design-database-using-azure-cli)
* [Postgres: create server + firewall rule](https://docs.microsoft.com/en-us/azure/postgresql/scripts/sample-create-server-and-firewall-rule?toc=%2fcli%2fazure%2ftoc.json)
* [Postgres: scale a server](https://docs.microsoft.com/en-us/azure/postgresql/scripts/sample-scale-server-up-or-down?toc=%2fcli%2fazure%2ftoc.json)
* [PHP + MySQL](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-tutorial-php-mysql?toc=%2fazure%2fmysql%2ftoc.json)
* [MySQL: create marketplace web app](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-create-web-app-from-marketplace?toc=%2fazure%2fmysql%2ftoc.json) :thumbsup:
* [MySQL: design a database](https://docs.microsoft.com/en-us/azure/mysql/tutorial-design-database-using-cli)
* [MySQL: create server + firewall rule](https://docs.microsoft.com/en-us/azure/mysql/scripts/sample-create-server-and-firewall-rule?toc=%2fcli%2fazure%2ftoc.json)
* [MySQL: scale a server](https://docs.microsoft.com/en-us/azure/mysql/scripts/sample-scale-server?toc=%2fcli%2fazure%2ftoc.json)
* [Developing a Java app using Azure Cosmos DB's MongoDB API](https://github.com/Azure-Samples/azure-cosmos-db-mongodb-java-getting-started)
* [Getting Started with Azure Search using Java](	https://github.com/Azure-Samples/search-java-getting-started)
* [A Simple Todo List Application built w/ Java + Azure DocumentDB](	https://github.com/Azure-Samples/documentdb-java-todo-app)
* [Flask on Docker with external PostgreSQL database](https://github.com/Azure-Samples/docker-flask-postgres) - [notes](docker-flask-postgres.md) :thumbsup:
* [Retwis - Twitter clone written in PHP with Redis](https://github.com/Azure-Samples/app-service-web-php-retwis)
* [Developing a Node.js app using Azure Cosmos DB](https://github.com/Azure-Samples/azure-cosmos-db-documentdb-nodejs-getting-started) :thumbsup:
* [How to use Azure Redis Cache with Python](https://docs.microsoft.com/en-us/azure/redis-cache/cache-python-get-started)
* [How to use Azure Redis Cache with Node.js](https://docs.microsoft.com/en-us/azure/redis-cache/cache-nodejs-get-started)
* [How to use Azure Redis Cache with Java](https://docs.microsoft.com/en-us/azure/redis-cache/cache-java-get-started)
* [Connect a web app in Azure App Service to Redis Cache via the Memcache protocol](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-connect-to-redis-using-memcache-protocol?toc=%2fazure%2fredis-cache%2ftoc.json)
* [Build an Azure Cosmos DB: API for MongoDB app using Node.js](https://docs.microsoft.com/en-us/azure/cosmos-db/mongodb-samples)
* [Use MongoChef with an Azure Cosmos DB: API for MongoDB account](https://docs.microsoft.com/en-us/azure/cosmos-db/mongodb-mongochef)
* [Use Robomongo with an Azure Cosmos DB: API for MongoDB account](https://docs.microsoft.com/en-us/azure/cosmos-db/mongodb-robomongo)
* [Microsoft Challenges - Azure Search](https://github.com/Microsoft/code-challenges/tree/master/Labs/Azure%20Search)
* [SQL Server on Linux on OpenShift](https://github.com/Microsoft/code-challenges/tree/master/Labs/SQL%20on%20Linux-Docker-OpenShift)
* [.Net Core, Docker and SQL Server on Linux](https://docs.docker.com/compose/aspnet-mssql-compose/)

## Continuous Deployment

[Section overview presentation (PDF)](presentations/03-Continuous-Deployment.pdf)

* [Movie Java Sample with Jenkins and Azure Container Service](https://github.com/Microsoft/movie-db-java-on-azure)
* [Sample Java webapp with Maven configuration to deploy to Azure App Service](https://github.com/Azure-Samples/app-service-maven)	
* [Contoso Moments](https://github.com/azure-appservice-samples/ContosoMoments) - no need to do Mobile component.
* [Advanced only: Deploy Team City using a Docker Image](https://hub.docker.com/r/jetbrains/teamcity-server/)
* [How to set up CI/CD with Buddy and Azure](https://hackernoon.com/how-to-set-up-ci-cd-with-buddy-and-azure-b9ec91e8c4ff)
* [Deploy to Kubernetes with Jenkins and Netflix Spinnaker](	https://github.com/Azure/azure-quickstart-templates/tree/master/301-jenkins-acr-spinnaker-k8s)
* [Push Docker Images to Azure Container Registry with Jenkins](	https://github.com/Azure/azure-quickstart-templates/tree/master/201-jenkins-acr)
* [Create a web app with continuous deployment from GitHub](	https://docs.microsoft.com/en-us/azure/app-service-web/scripts/app-service-cli-continuous-deployment-github)
* [Create a web app and deploy code from a local Git repository](	https://docs.microsoft.com/en-us/azure/app-service-web/scripts/app-service-cli-deploy-local-git?toc=%2fcli%2fazure%2ftoc.json)
* [Create a web app and deploy code to a staging environment](	https://docs.microsoft.com/en-us/azure/app-service-web/scripts/app-service-cli-deploy-staging-environment?toc=%2fcli%2fazure%2ftoc.json)
* [Deploy your app to Azure App Service using FTP/S](	https://docs.microsoft.com/en-us/azure/app-service-web/app-service-deploy-ftp)
* [Agile software development with Azure App Service (Windows)](	https://docs.microsoft.com/en-us/azure/app-service-web/app-service-agile-software-development)
* [Flighting deployment (beta testing) in Azure App Service (Windows)](	https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-test-in-production-controlled-test-flight)
* [Get started with test in production for Web Apps](	https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-test-in-production-get-start)
* [Atlassian: Deploy to Microsoft Azure](https://confluence.atlassian.com/bitbucket/deploy-to-microsoft-azure-900820699.html)
* [Github: Automating code deployment with GitHub and Azure](https://github.com/blog/2056-automating-code-deployment-with-github-and-azure)

## Containers

[Section overview presentation (PDF)](presentations/04-Containers-and-day-summary.pdf)

* [Getting started with Azure Kubernetes (AKS) clusters](https://docs.microsoft.com/en-gb/azure/aks/tutorial-kubernetes-prepare-app)
* [Containers on Azure - Intro Lab](https://github.com/shanepeckham/ContainersOnAzure_IntroLab)
* [Manage Linux Web App With Container Registry - in Java](https://github.com/Azure-Samples/app-service-java-deploy-image-from-acr-to-linux)
* [Azure Container Instances Quick Start](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-quickstart) :thumbsup:
* [Azure Container Intances Multi-container groups](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-multi-container-group)
* [Azure Container Intances - mounting Azure Files Volumes](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-mounting-azure-files-volume)
* [Azure Voting App](https://github.com/Azure-Samples/azure-voting-app)
* [Hosting Jekyll on Azure App Service on Linux](http://anthonychu.ca/post/jekyll-azure-app-service-linux/)
* [Jenkins integration with Azure Container Service and Kubernetes](https://docs.microsoft.com/en-us/azure/container-service/container-service-kubernetes-jenkins)
* [Cool Store JBoss BRMS demo (run on a container in ACS or App Service)](https://github.com/jbossdemocentral/brms-coolstore-demo)
* [Deploy to Kubernetes with Jenkins and Netflix Spinnaker](https://github.com/Azure/azure-quickstart-templates/tree/master/301-jenkins-acr-spinnaker-k8s)
* [Use Helm to deploy containers on a Kubernetes cluster](https://docs.microsoft.com/en-us/azure/container-service/container-service-kubernetes-helm)
* [Use Draft with Azure Container Service and Azure Container Registry to build and deploy an application to Kubernetes	](	https://docs.microsoft.com/en-us/azure/container-service/container-service-draft-up)
* [Push Docker Images to Azure Container Registry with Jenkins](https://github.com/Azure/azure-quickstart-templates/tree/master/201-jenkins-acr)
* [Geo-replication with Azure Container Registry](https://docs.microsoft.com/en-au/azure/container-registry/container-registry-tutorial-prepare-registry)
* [Create a private Docker container registry using the Azure CLI 2.0	](https://docs.microsoft.com/en-au/azure/container-registry/container-registry-get-started-azure-cli)
* [Manage an Azure Container Service DC/OS cluster through the Marathon web UI](https://docs.microsoft.com/en-us/azure/container-service/container-service-mesos-marathon-ui)
* [Enable public access to an Azure Container Service application (DC/OS)	](https://docs.microsoft.com/en-us/azure/container-service/container-service-enable-public-access)
* [Canary release microservices with Vamp on an Azure Container Service DC/OS cluster](https://docs.microsoft.com/en-us/azure/container-service/container-service-dcos-vamp-canary-release)
* [Deploy a Spring Boot application on Linux in the Azure Container Service](https://docs.microsoft.com/en-us/azure/container-service/container-service-deploy-spring-boot-app-on-linux)
* [Deploy a Spring Boot Application on a Kubernetes Cluster in the Azure Container Service](https://docs.microsoft.com/en-us/azure/container-service/container-service-deploy-spring-boot-app-on-kubernetes	)
* [Run applications in Kubernetes (uses Voting App sample).](https://docs.microsoft.com/en-us/azure/container-service/container-service-tutorial-kubernetes-deploy-application)
* [Scale Kubernetes pods and Kubernetes infrastructure](https://docs.microsoft.com/en-us/azure/container-service/container-service-tutorial-kubernetes-scale)
* [Update an application in Kubernetes](https://docs.microsoft.com/en-us/azure/container-service/container-service-tutorial-kubernetes-app-update)
* [Load balance containers in an Azure Container Service DC/OS cluster](https://docs.microsoft.com/en-us/azure/container-service/container-service-load-balancing)
* [Use ACR with a DC/OS cluster to deploy your application](https://docs.microsoft.com/en-us/azure/container-service/container-service-dcos-acr)
* [Deploy and use Azure Container Registry](https://docs.microsoft.com/en-us/azure/container-service/container-service-tutorial-kubernetes-prepare-acr)
* [Using a custom Docker image for Azure Web App on Linux](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-linux-using-custom-docker-image)
* [Deploying a JSP Web App to Azure App Service](https://alexandrebrisebois.wordpress.com/2015/09/15/azure-adventures-deploying-a-jsp-web-app-to-azure-app-service/)
* [Azure Batch Python Samples](https://github.com/Azure/azure-batch-samples/tree/master/Python/Batch)
* [Running CoreOS Container Linux on Microsoft Azure](https://coreos.com/os/docs/latest/booting-on-azure.html)
* [Deploy container app (Service Fabric)](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-deploy-container-linux)
* [Docker Compose application support in Azure Service Fabric (Preview)](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-docker-compose)
