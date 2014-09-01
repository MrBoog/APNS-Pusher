# APNS Pusher
A simple debug application for Apple Push Notification Service (APNS).

[Download the latest version](https://github.com/blommegard/APNS-Pusher/releases "Download") 

## Features
* Send push notifications to APNS (Apple Push Notification Service) very easily (no configuration needed at all)
* Grabs the certificate right from your keychain
* Get the device token automatically via Bonjour; forget about manually retrieving the device token through logging or similar techniques. Useful when not in sandbox mode
* Support for error response codes
* Detects Development/Production environment automatically
* Custom JSON payloads
* Identity export to PEM format (⌘ + E)

## Usage of automatic token detection (iOS6+)
* Copy the files SBAPNSPusher.h/m to your project
* …or use [Cocoapods](http://cocoapods.org/):
 ```ruby
pod "SBAPNSPusher"
 ```

* Run the following code in ```application:didFinishLaunchingWithOptions:```

 ```objective-c
[SBAPNSPusher start];
 ```

* Start the app and make sure you're on the same wifi

## Screenshots
![Screenshot](https://github.com/blommegard/APNS-Pusher/raw/master/Screenshots/main.png "Main")
![Screenshot](https://github.com/blommegard/APNS-Pusher/raw/master/Screenshots/certificates.png "Certificates")


## License
APNS Pusher is released under the MIT-license (see the LICENSE file)
