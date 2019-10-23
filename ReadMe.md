# ASP.Net Core Samples

# Web API - Hello World 
Project Name: hello-world-webapi

* List all dotnetcore templates
```
dotnet new -l
```

* Create a webapi project
```
dotnet new webapi -o hello-world-webapi
```

* Trust the development certificate
```
dotnet dev-certs https --trust
```

* Run the app
```
cd hello-world-webapi
dotnet watch run
```

* Test
Browse to [https://localhost:5001/WeatherForecast](https://localhost:5001/WeatherForecast)

# gRPC - Hello World

```
dotnet new grpc -o hello-world-grpc
```