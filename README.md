# Duplicate Repositories issue with Grails 2.x

## Steps to reproduce:
* fire up a simple http server `$ python -m SimpleHTTPServer 12345`
* `grails compile`

Note that "GET /batman/was/here/was-here.jar HTTP/1.1" and "GET /batman/was/here/was-here.pom HTTP/1.1" was repeated excessively.


