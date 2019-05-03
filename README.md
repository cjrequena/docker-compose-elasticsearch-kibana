# Elasticsearch & Kibana powered by compose

## Requirements:
* docker >= 18.09.0+
* docker-compose

## Quick Start
* Clone or download this repository
* Go inside of directory,  `cd docker-compose-elasticsearch-kibana`
* Run this command `docker-compose up -d`

## Environments
This Compose file contains the following environment variables:

* `CLUSTER_NAME` the default value is **docker-cluster**

## Access to Elasticsearch: 
* `localhost:9200`

## Access to Kibana: 
* **URL:** `http://localhost:5601`
