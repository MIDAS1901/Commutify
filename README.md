# Commutify
## A realtime chat application/ Partial Whatsapp Clone


The application is entirely created using XML, Java and Firebase. The project uses additional libraries such as:

1) [Country Code Picker(CCP)](https://github.com/hbb20/CountryCodePickerProject) : Implemented for fetching the country code of user; required for OTP sent to user's phone number. 
2) [Picasso](https://github.com/square/picasso) : Implemented for loading and caching display profile pictures of the current and other users.


## Features
:white_check_mark: Authentication of a User through their Phone Number (OTP Verification using **Firebase Authentication**)

:white_check_mark: Option for User to choose their Display Profile Picture and Username; also they can change it later (Storing the images on **Firebase Cloud Storage**)

:white_check_mark: View the Username, Activity Status (Online/Offline) and Display Profile Picture of Other Users (Retrieved through **Firebase Cloud Firestore**)

:white_check_mark: Chat in realtime with another User (Data Stored and Retrieved through **Firebase Realtime Database**)   


## Preview

![image](https://user-images.githubusercontent.com/62807226/105393870-e389fc00-5c42-11eb-82fc-7466c00f08b2.png)


## Minimum SDK
  
  Android 6.0 (Marshmallow).

## Installation Instructions
1. Clone the repository.
2. Use `Import Project` in Android Studio.
3. Try it out on your Physical Device or Emulator.

## Possible Updates
- [ ] Automatically fetch the OTP from SMS
- [ ] Group chat
- [ ] Calling Feature
- [ ] UI Improvements 
- [ ] Status Feature (getting ambitious here)
