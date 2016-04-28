# ExpressAPIGateway
Simple API Gateway with ExpressJS
It works but is only used as an example. You may need to fit it your needs!

A detailed code description can be found at: http://www.sascha.tech/2016/02/05/building-a-simple-api-gateway-with-expressjs/

####Install NodeJS
https://nodejs.org/en/

####Install dependencies:
npm install --dev-save expressjs request

####Setup your API definition
Open the api-def.json and add each host you want to provide the services from. For each host you can add as many redirects as you want and according methods.

You  may want to modify the code because the used JSON is very verbose and could be optimized.

####Start
node server.js
