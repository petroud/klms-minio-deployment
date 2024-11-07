# KLMS MinIO with NGINX Triple Instance Deployment
This project deploys 3 MinIO instances and lies them behind a NGINX proxy routing traffic to them from 3 different sets of domain names. It is used in the KLMS STELAR EU

### Before deploying make sure for the following:

- /certs dir is present containing a __fullchain.pem__ and a __privkey.pem__ file corresponding to a wildcard certificate for your base domain name.
- .env file has the password and username set upon desire. 
