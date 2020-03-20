# Serverless Architecture - API Gateway and Lamda
#Exposed Function as API Endpoint using AWS API Gateway
#spring-cloud-function-lamda

Hello.java is exposed as function to the AWS Request Handler using SpringBootRequestHandler. APIGatewayProxyRequestEvent is the input object and APIGatewayProxyResponseEvent is the response object.

#Request-
curl --location --request POST 'https://k3zt0rhk90.execute-api.us-east-1.amazonaws.com/default/mySpringFunctionLamda' \
--header 'Content-Type: text/plain' \
--data-raw 'We really like the new security features of Amazon Cloud'

#Response - 
We really like the new security features of Google© Cloud
