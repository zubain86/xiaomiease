# Xiaomiease-
The basic idea to build this application is to write a common code that can work on android, iOS and windows. To achieve this following cross platform technologies are used-<br/>
(1) Flutter <br/>
(2) Firebase <br/>
(3) GetX <br/>
# About the application-
To understand well about the application let's first get insights of the technologies used-
## Firebase-
Firebase provides various services like authentication, real time hosting of databases, notifications and various set of hosting services for any type of application. This application is capable of utilising all the services provided by the firebase but as of now it is using authentication service.<br/>
Dummy User:<br/>
ID-<br/>
miuser@gmail.com <br/>
Password- <br/>
000000<br/>
![Screenshot (99)](https://user-images.githubusercontent.com/96322986/190841825-0dfa2c51-4ee5-431a-8b68-c22186856be9.png)

![Screenshot (100)](https://user-images.githubusercontent.com/96322986/190843194-0e672be6-9956-4db7-815e-5511019bdede.png)

## Flutter + GetX-
Dart is the programming language used to code Flutter apps. Both frontend and backend is written in dart.A basic pubspec is generated when you create a new Flutter project. It's located at the top of the project tree and contains metadata about the project that the Dart and Flutter tooling needs to know. 
#### Frontend
Flutter includes a full set of widgets that deliver pixel-perfect experiences whether you're building for iOS (Cupertino) or other platforms (Material), along with support for customizing or creating entirely new visual components.
#### Backend
Flutter code is powered by the world-class Dart platform, which enables compilation to 32-bit and 64-bit ARM machine code for iOS and Android, as well as JavaScript for the web and Intel x64 for desktop devices.
To know more - https://github.com/flutter/flutter
#### GetX
When flutter is capable of handling frontend and backend both then why getx is used?? <br/>
It is a library in flutter that can perform simplified-<br/>
(1) State Management <br/>
(2) Route Management <br/>
(3) Dependancy Management <br/>
It simply eases the backend management in flutter apps.<br/>
To know more - https://blog.logrocket.com/ultimate-guide-getx-state-management-flutter/<br/>
So all these features help to optimize code in invoice building and increases productivity and performance. 

## Features-
### Create professional invoices-

![Screenshot (101)](https://user-images.githubusercontent.com/96322986/190843897-c3892974-0b99-433a-a5ca-a24e1657f54a.png)

### Operator details-

![Screenshot (102)](https://user-images.githubusercontent.com/96322986/190843918-181dc8e5-1c05-4ba3-8dd6-4df56ba2e02a.png)

### Customer details-

![Screenshot (103)](https://user-images.githubusercontent.com/96322986/190843942-b1b5772d-e8b3-4c23-826d-8ff4d3920c80.png)

### Add multiple items-

![Screenshot (104)](https://user-images.githubusercontent.com/96322986/190843964-9000a8c1-8a9d-4118-bdf1-c308ddfbb154.png)

### Preview invoices-

![Screenshot (106)](https://user-images.githubusercontent.com/96322986/190844132-bedbe575-7c3e-4e4c-ae5b-40f389572840.png)

### Download invoices-
For downloading invoices specified path is `/storage/emulated/0/Android/data/com.example.xiaomiease/files`. _These folders need to be present in your emulator or device otherwise error will be shown while downloading._

![Screenshot (107)](https://user-images.githubusercontent.com/96322986/190844375-0099843d-bff0-4cc8-a218-d9157601d9be.png)

### Send invoices-

![Screenshot (108)](https://user-images.githubusercontent.com/96322986/190844391-e4e22186-e04a-49b5-b3f0-a7e45396fa91.png)

### Make payment using gpay-

![Screenshot (109)](https://user-images.githubusercontent.com/96322986/190844565-755a2456-12e4-4abd-9415-edd4b741520f.png)

# How to run? 

_Make sure you have flutter installed in your system - https://docs.flutter.dev/get-started/install_

(1) Clone the repository into your system using command `git clone https://github.com/zubain86/xiaomiease` <br/>

(2) Open the folder in IDE. Visual Studio Code is preferred. <br/>

(3) Now open the terminal and make sure you are in the root directory of the application. Write command `flutter pub get`.
    It will install all the packages missing in your system. <br/>

![Screenshot (110)](https://user-images.githubusercontent.com/96322986/190849220-89dcca41-7eba-4ee1-9d68-f878dce5e8e2.png)

(4) Now there are two ways to run the app. <br/>

(a) Using Android Emulator- <br/>

-Make sure you have an android emulator installed in your system. <br/>
        
-Now write command `flutter run`  <br/>    

![Screenshot (112)](https://user-images.githubusercontent.com/96322986/190849437-01165e58-cfcf-45cf-be76-d06f789024ab.png)

-App will start running <br/>

(b) On device- <br/>

-Write command `flutter build apk` <br/>

-Go to the indicated path....Install it in your device and run it. <br/>

![Screenshot (113)](https://user-images.githubusercontent.com/96322986/190849630-8056dac0-729e-4a0f-8e3b-8a39a400d52d.png)

#### Apk link - https://drive.google.com/drive/folders/1nQ3i4IPCSizpCLFB11axa9o82f1yoWWC?usp=sharing

#### Video Link- https://youtu.be/TvNaqlkUFjI


_Since it is a prototype so firebase authentication is done only for android so it is recommended to run it on android only. After adding certain dependancies it will work fine for iOS, Windows and even Web._  

