# Getting Started
## How to Build


The generated code has dependencies over external libraries like UniRest, JSONModel and ISO8601DateFormatter. These dependencies are defined in the ```PodFile``` file that comes with the SDK. 
To resolve these dependencies, we use the Cocoapods package manager.
Visit https://guides.cocoapods.org/using/getting-started.html to setup Cocoapods on your system.
Open command prompt and type ```pod --version```. This should display the current version of Cocoapods installed if the installation was successful.

1. Using command line, navigate to the directory containing the generated files (including ```PodFile```) for the SDK. 
2. Run the command ```pod install```. This should install all the required dependencies and create the ```pods``` directory in your project directory.

![Installing dependencies using Cocoapods](http://apidocs.io/illustration/ObjC?step=AddDependencies&projectName=Tester)

3. Open the project workspace using the (Tester.xcworkspace) file.
4. Invoke the build process using `Command(⌘)+B` shortcut key or using the `Build` menu as shown below.

![Building SDK using Xcode](http://apidocs.io/illustration/ObjC?step=BuildSDK)

## How to Use

The following section explains how to use the Tester library in a new console project.     


## Initialization



# Class Reference
