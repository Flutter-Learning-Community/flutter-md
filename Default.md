# Default 

## App Logo

* ### First we Choose the app logo suitable for the app.

* ###   flutter_launcher_icons: ^0.7.4 --> Add the package in pubspec. yaml file.
* ### And add the following code 
    * flutter_icons:
    * image_path: "asset/image.jpg"
  * android: true
  * ios: true

* Open terminal and run the command
    * flutter pub get 
* after run this command 
    * flutter pub run flutter_launcher_icons:main
* Next flutter run

    
     
---
# ENV
## How to create 
* Our project root file to create a .env file for using the environment variable.

## How to use.
* Inside the .env file we use the common variable name(name) + insert the end point

* Add the Package in Pubspec.yaml file
    * flutter pub add dotenv
* And call the function in main.dart file 

* In API call the variable name instead of endpoint.
---
# Permission Access 

## How to give the access permission like camera .

* Path for adding gradle properties
    * android --> gradle.properties
        * Inside that add this android.enable DexingArtifactTransform=false
* Android mainfest.xml path

    * android-->app-->src-->debug--> Android mainfest.xml 
        * Inside that add what are the permission you want to add.
---
# Basic File Structure
* .dart_tool
* .idea
* android
* assets
    * fonts
    * images
    * logo
    * videos
* cloud_functions
* ios
* lib
    * blocs
    * models
        * user.dart
    * data
    * providers
    * screens
        * home.dart
    * utilities 
        * logic.dart
    * services 
    * widgets
        * appbar.dart
    * main.dart
* test
* web 

    



