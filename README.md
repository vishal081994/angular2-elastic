## Description

* Elasticsearch example, developed with angular 2 (b8)

##First of all
* Install elasticsearch server according to [instructions](https://www.elastic.co/guide/en/elasticsearch/reference/current/_installation.html).
* Add this lines to your elasticsearch.yml (it's not recommended in real app):

```yml
http.cors.enabled : true 
http.cors.allow-origin : "*"
http.cors.allow-methods : OPTIONS, HEAD, GET, POST, PUT, DELETE
http.cors.allow-headers : X-Requested-With,X-Auth-Token,Content-Type, Content-Length
```

## Quick start
Install:
```bash
npm install -g typings webpack webpack-dev-server
npm install
```
Build:
```bash
npm start build
```
Start in dev mode (awailable on [localhost:3030](localhost:3030) by default)
```bush
npm start dev
```
Follow this steps: 
1. Go to admin tab and add something to the elasticsearch index using provided form
2. Go back to the client page
3. Search is performed by title field by default!