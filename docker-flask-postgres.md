### Tips for Docker Flask Postgres Web App

The easiest way to get going with this lab if you don't have Docker locally (or the bandwidth to download all the bits to your local environment) is to create an Ubuntu VM in Azure.

* Create a Ubunutu 16.04 LTS VM from the Azure Marketplace.

* Use an existing Azure Database for Postgres Instance
  * [Disable SSL](https://docs.microsoft.com/en-us/azure/postgresql/concepts-ssl-connection-security) (yes, I know, this for a demo only...)
  * [Allow inbound connections](https://docs.microsoft.com/en-us/azure/postgresql/concepts-ssl-connection-security) from the IP address of the VM you created above
  * Note down the server name, username and password for access. We'll just use the default 'postgres' database for this lab.

* SSH into the VM you created above and install Docker using
```
 sudo apt install docker.io
 ```
 * Clone the repository
```
 git clone https://github.com/Azure-Samples/docker-flask-postgres.git
```
* Build and run the Flask application as per the instructions supplied with sample. Note you'll need to use sudo.

Note: get added bonus points if you can figure out how to push the image to an [Azure Container Registry](https://docs.microsoft.com/en-us/azure/container-registry/container-registry-get-started-docker-cli) and then deploy to an [Azure Container Instance](https://blogs.msdn.microsoft.com/stevelasker/2017/07/28/deploying-docker-images-from-the-azure-container-registry-to-azure-container-instances/). 
