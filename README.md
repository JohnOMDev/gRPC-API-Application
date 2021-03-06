## Project Overview

A microservice project that uses gRPC API to request and get response from the server to the client. gRPC is a remote procedure call (RPC) framework from Google. It uses Protocol Buffers as a serialization format and uses HTTP2 as the transport medium. In gRPC, a client application can directly call methods on a server application on a different machine as if it was a local object; this process makes it easier to create distributed applications and services.

### Project Tasks

#####   The project is Language-independent gRPC-based microservice:
###### Client Python
###### Sever- Python
* Create a gRPC server (in your preferred language) that serves the time-based electricity consumption data found in the attached file: meterusage.csv.
* Use whatever tool you prefer to create an http server that will request the data from the gRPC server and deliver the consumption data as JSON. 
*  Create a single page html document that requests the JSON from the http server and displays it. Please supply a link to your work in a public repository and a short README with a description of what you did."

![pasted image 0](https://user-images.githubusercontent.com/50584494/85916907-6c7bb900-b855-11ea-9c47-6e9fb087d305.png)

## Project Implementation


![projectflow](https://user-images.githubusercontent.com/50584494/85916921-a056de80-b855-11ea-8bfd-8cdd83ba2b26.PNG)



## Running the project
1. Run the make setup file in the Makefile for environment setu and cd into the environment:  `make setup`
2. Run the make install file to install all requirements in the requirements.txt and update or install the python:  `make install`
3. Run the make install file to install all requirements in the requirements.txt and update or install the python--Note that it should not be run orlese you wannna experiment with the structure  `gRPCSetUp:`
4. Standalone lastly, both should be run on two different CLI:  `python server.py`, `python client.py` and should run on `http://127.0.0.1:5000/`
5. Delete Everything:  `./delete.sh`

## To confirm running

#####   Server Output: Starting server. Listening on port 50051.
#####   Client output :
* Serving Flask app "client" (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: on
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 284-303-386
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)

 #####  Broswer output
![spe Img](https://user-images.githubusercontent.com/50584494/85916834-a26c6d80-b854-11ea-9539-83e40152e959.PNG)


![spe Img2](https://user-images.githubusercontent.com/50584494/85916835-a3050400-b854-11ea-9f80-a8bed3ab017c.PNG)



##  Next
*   Containerized through docker
*   Hadolint
*   Responsive UserInterface
