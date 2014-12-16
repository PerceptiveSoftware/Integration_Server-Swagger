Integration_Server-Swagger
==========================


Installation
-------------------

0. Copy 'api' directory to web server directory.

1. Update 'path' variables in 'api/api-docs' file to point to webserver address.
'''
example -- "path" : "http://apidocs.psft.co/api/listings/drawer"
'''

2. Update 'basePath' variable in listing files to point to Integration Server URL.
'''
	example file path-- file (/api/listings/applicationPlan)
	example variable -- "basePath" : "http://apidocs.psft.co/integrationserver"
'''

3. Test interface connectivity by browsing to instance deployment.
'''
	example -- "http://apidocs.psft.co/api"
'''