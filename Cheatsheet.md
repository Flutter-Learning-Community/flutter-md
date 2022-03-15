# Basic Git Commands 

## Null-safety Command

*  flutter run --no-sound-null-safety


## Flutter path error

The command could not be located because '/snap/bin' is not included in the PATH environment variable

For this Error

* ### Temporary solution:
    
    * Run the command export PATH=$PATH:/snap/bin



* ### Permanent solution:
    
    * Edit /etc/environment and add /snap/bin in the list then restart your system.

## Add pub packages through command line 

* flutter pub add  < package name >.

## Built APK 
*  flutter build apk --debug.

## Built IPA

* flutter build ios --debug.


## To run the app

* Through commandline --> flutter run.
* Click Run->start Debugging (or) click F5.

### flutter doctor -->  setting up the local development environment for both iOS and Android.