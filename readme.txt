==============
nest-cors-test
==============

-------------------------------------------------------------------------------------
Usage
=====

- server:
	- go to nest-cors-test-server
	- npm start 
	
	resource: http://localhost:3000/user
	
- client
	- go to nest-cors-test-client
	- npm start 

	test page: http://localhost:8080
	
	
-------------------------------------------------------------------------------------
Explanation
===========
CORS can be enabled in main.ts:

	app.enableCors();
	
  It adds header parameter to REST responses:

	Access-Control-Allow-Origin: *
	
	
	
