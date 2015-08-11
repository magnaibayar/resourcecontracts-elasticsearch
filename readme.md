# NRGI- Elasticsearch API

## Install

NRGI-Elasticsearch API can be cloned from gitlab repository and installed. Following the procedure given below:

* git clone git@gitlab.yipl.com.np:web-apps/rces.git
* cd rces
* add `127.0.0.1 rces.dev` to your `/etc/hosts` file
* change your apache host file
* restart apache server

## Run

The app can be run with the command below:

* install the application dependencies using command: `composer install`

## Setup Elasticsearch

### For Linux

* Download Elasticsearch- `wget https://download.elastic.co/elasticsearch/elasticsearch/elasticsearch-1.5.2.deb`
* `sudo dpkg -i elasticsearch-1.5.2.deb`
* Start Elasticsearch Service `sudo service elasticsearch restart`

## Tools and packages

This application uses following packages:

* [ElasticSearch PHP client](https://github.com/elastic/elasticsearch-php) - for Elastic Search API 
* [League Route](http://route.thephpleague.com/) - for Routing 
* [PHP dotenv] (https://github.com/vlucas/phpdotenv) - for loading environment variables

