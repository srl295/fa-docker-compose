Docker-Compose for frontaccounting
===

To use:
---


1. Install docker-compose
2. `docker-compose up`
3. Browse to port 3080 on your docker host: http://whatever.example.com:3080
4. when you configure FA, use these options:

	- MYSQL_PASSWORD=PZp6nT9y9Fano4vMJtmmGLxcY
    - MYSQL_USER=fa
    - MYSQL_DATABASE=fa
    - MYSQL_HOST=database

5. data lives in `./data` (mysql dir)

Disclaimer/notes
---

- I can't help you use FrontAccounting. I don't really know myself.
- Mysql 5.5 used, see [here](http://frontaccounting.com/punbb/viewtopic.php?pid=19815#p19815)

Links
---

* Dockerfile/image: genebarker/frontaccounting [github](https://github.com/genebarker/frontaccounting) [docker](https://hub.docker.com/r/genebarker/frontaccounting/)
* FrontAccounting: http://frontaccounting.com/fawiki/
