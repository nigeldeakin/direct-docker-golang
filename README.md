# direct-docker-golang
An example of a wercker pipeline that uses a direct docker daemon

## Set environment variables

Configure your application with the following environment variables 
* `USERNAME` - Your Docker Hub username 
* `PASSWORD` - Your Docker Hub password
* `PROD_OR_STAGING` - A string used to distinguish between any workflows that might be run concurrently (must be lower case)

