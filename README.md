# workshop-apache-kafka-connect

Hand-outs with assignments will be given at the workshop.

this was clone from this repo: https://github.com/rvanrijn/workshop-apache-kafka-connect.git

1. start your fast-data-dev
```
	docker-compose -f docker-compose-lab-priv_net-ext.yaml up -d
```
2. start your lense.io
you must check for fast-data-dev environments was deployed in first step and checking for there ```ip address``` of container of 
```kafka-cluster_1```
```mongo-express_1```
```elasticsearch_1```
```redis_1```
putting them into following file ```docker-compose-lab-lenses-host_net.yaml``` and running following
```
	docker-compose -f docker-compose-lab-lenses-host_net.yaml up -d 
	
```
3. start your dev environment
```
	docker-compose -f docker-compose-lab-devenv-priv_net.yaml up -d
```


### Congragulation you finnish running the fast-data-dev workshop environment and ready to dev and deploy code to test any microservice solution you want 

