# dotnet-6-minimal-api

A minimal Web API created by .NET 6.0

# Create a global json

dotnet new globaljson --sdk-version 6.0.320 --force

# Functionality of the Web App

- A Simple Web API
- Display a list of Products
- Display a Product by a Id

# Tech used for creating the Web App

- A .NET 6 Web API
- A traditional Webhotel for hosting
- VS Code

# Development

dotnet run

# Production

Create a self contained build for production at the remote server / traditionel web hotel

dotnet publish webapi.csproj --configuration Release --runtime win-x86 --self-contained

Upload the build to remote server

At my remote servers the web.config needs to be without the folowing:

hostingModel="inprocess"

# Test the Web API

- yourhost/products

- yourhost/products/1

