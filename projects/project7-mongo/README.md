## Mongo and Mongo Express

## We will use deployments, services, configMaps and Secrets to see how doe they all work together.

## Mongodb has an internal service and use secrets variable. Mongo express uses that service of mongodb as database_url. This url is specified in a configmap file. Then those values are taken from congifMap and secret and placed to deployments. At the end, mongo-express uses a service to let the users access their pods in mongo-express deployment.
