## DreamHouse Mobile App

1. Install Cordova and the latest beta version of the Ionic CLI:
    ```
    npm install -g cordova ionic@beta
    ```

1. Clone this repository
    ```
    git clone https://github.com/dreamhouseapp/dreamhouse-mobile-app
    ```
    
1. Navigate to the dreamhouse-mobile-app directory:
    ```
    cd dreamhouse-mobile-app
    ```

1. Install the dependencies
    ```
    npm install
    ```
    
1. Remove the default version of Cordova iOS
    ```
    cordova platform remove ios
    ```
    
1. Install the version of Cordova iOS required by the Mobile SDK
    ```
    cordova platform add ios@3.9.2
    ```

1. Install the Mobile SDK plugin
    ```
    cordova plugin add https://github.com/forcedotcom/SalesforceMobileSDK-CordovaPlugin
    ```

1. Build the app for iOS
    ```
    ionic build ios
    ```

1. Open ```DreamHouse.xcodeproj``` in the ```dreamhouse-mobile-app/platforms/ios``` directory  

1. In Xcode, run the application, or select Product>Archive in the menu for App Store or Enterprise deployment