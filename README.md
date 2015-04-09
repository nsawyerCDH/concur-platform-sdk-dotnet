Concur Platform SDK for .NET Framework and Xamarin
==================================================

This SDK contains the following:
* .NET Portable Class Library source code (which also works on Xamarin) for abstracting details on how to call and consume Concur web services.
* Source code for an Android sample app that uses the portable library to call Concur web services.
* Source code for an iOS sample app that uses the portable library to call Concur web services.
* Source code for a Windows sample app that uses the portable library to call Concur web services.

## Installation

The portable class library included in this SDK is already compiled and uploaded at [http://www.nuget.org/packages/ConcurPlatform](http://www.nuget.org/packages/ConcurPlatform) as a Nuget package, named "*ConcurPlatform*".




To reference the 

The source code contained in this repository is self-contained and it doesn't have external references.

## User Credentials

The portable library requires user credentials in order to make web services calls on the behalf of a user. If you want, you can obtain user credentials to a brand new sandbox company at Concur by [following the sandbox registration process described here](https://developer.concur.com/register).  








You need user credentials in order to call 

To install Concur Platform from inside the [Package Manager Console](http://docs.nuget.org/docs/start-here/using-the-package-manager-console), run the following command:

    Install-Package ConcurPlatform

Otherwise, to install Concur Platform using the [Nuget command line tool](https://docs.nuget.org/consume/command-line-reference), run the following command:

    nuget install ConcurPlatform

NOTE: Navigate to http://www.nuget.org/packages/ConcurPlatform/ if you want to see further information about the ConcurPlatform package.



## --------------------------- BEGIN Parking Lot Text ---------------------------------------

abstracting calls for the following web services in the concur platform:

SDK for the [Concur Platform](http://developer.concur.com). For more information on the set of platform services, see the [Web services overview](https://developer.concur.com/get-started/webservices-overview) document on the developer portal.
Register for a [developer Sandbox here](https://developer.concur.com/register).

## --------------------------- END Parking Lot Text ---------------------------------------






## License

Copyright 2014 [Concur](http://www.concur.com)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
