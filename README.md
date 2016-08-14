# GladLive.ModuleService.ASP

GladLive is network service comparable to Xboxlive or Steam. 

GladLive.ModuleService.ASP provides a web scalable skeleton webservice/web-api that can be extended with the GladLive.Module.System and communicate with others in the distributed network providing:
  - HTTPS/TLS ASP Service
  - Skeleton Application for Module registration

## How to User

Register the modules in the modules.json file and database configuration options in the database.json file. The application will handle registering the modules on startup.

## Setup

To use this project you'll first need a couple of things:
  - Visual Studio 2015 RC 3
  - ASP Core VS Tools
  - Dotnet SDK
  - Add Nuget Feed https://www.myget.org/F/hellokitty/api/v2 in VS (Options -> NuGet -> Package Sources)

## Builds

Available on HelloKitty Nuget feed:  https://www.myget.org/F/hellokitty/api/v2

##Tests

#### Linux/Mono - Unit Tests
||Debug x86|Debug x64|Release x86|Release x64|
|:--:|:--:|:--:|:--:|:--:|:--:|
|**master**| N/A | N/A | N/A | [![Build Status](https://travis-ci.org/GladLive/GladLive.ModuleService.ASP.svg?branch=master)](https://travis-ci.org/GladLive/GladLive.ModuleService.ASP) |
|**dev**| N/A | N/A | N/A | [![Build Status](https://travis-ci.org/GladLive/GladLive.ModuleService.ASP.svg?branch=dev)](https://travis-ci.org/GladLive/GladLive.ModuleService.ASP)|

#### Windows - Unit Tests

(Done locally)

##Licensing

This project is licensed under the MIT license with the additional requirement of adding the GladLive splashscreen to your product.
