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

### -> Signup Screen and OTP Verification

![login](https://user-images.githubusercontent.com/62807226/127671530-41b0bfd1-6805-40fc-8950-084b026517e5.gif)


### -> Realtime chat between two users


![user 1's screen](https://user-images.githubusercontent.com/62807226/127674321-1c55537a-2174-43ec-ae45-36cb89d095ec.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![user 2's screen](https://user-images.githubusercontent.com/62807226/127674343-f04cd600-b912-4fda-afda-8116b39b3ba6.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*User 1's Screen*&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*User 2's Screen*


## Download
If you wanna try it out for yourself you can click on the hyperlink link below and download the apk.

[Commutify.apk](https://drive.google.com/file/d/1L_uYEKqGuAj6ggRw0P4il8YrX_J2P2VW/view?usp=sharing)

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
