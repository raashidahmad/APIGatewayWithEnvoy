# API Gateway using Envoy (ASP.NET Core)
## Introduction

This is a sample project demonstrating the usage of Envoy to build the API Gateway using Envoy. The project uses the docker to build the images for each project (Mimicking a microservice). Docker compose uses the individual images and configuration file from the Envoy to build the API Gateway.

After successfully running the docker compose the application listens on the port 10000 using http while https may be accessed using 10001. The credit for this sample project goes to the tutorial video designed by Las Jackson.

Video URL:
[API Gateway using Envoy](https://www.youtube.com/watch?v=UsoH5cqE1OA&t=2s)
