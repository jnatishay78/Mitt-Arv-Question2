# Mitt-Arv-Question2

E-commerce App This guide provides instructions for setting up the E-commerce app built using Flutter. The app utilizes various packages for state management, responsive UI design, and theming.

Prerequisites Before setting up the project, ensure you have the following installed on your machine:
Flutter SDK: Install Flutter Dart SDK: Included with the Flutter installation Android Studio or VS Code Git: Install Git for version control
Project Setup Follow the steps below to set up the project:

Clone the Repository:
git clone https://github.com/jnatishay78/Mitt-Arv-Question2.git 
cd your-repository

Install Dependencies: Navigate to the project directory and run the following command to install the required Flutter packages:
flutter pub get Run the App:

Use the following command to run the app on your connected device or emulator:
flutter run Key Packages Used The app makes use of several Flutter packages to enhance functionality:
flutter_screenutil: Used for responsive UI design to adapt to different screen sizes. get: A powerful state management and navigation package. shared_preferences: Used to store and retrieve simple data persistently (wrapped in the custom MySharedPref class). Main Components main.dart: The entry point of the application. It initializes necessary configurations such as shared preferences and sets up the GetMaterialApp. MySharedPref: A custom wrapper around shared preferences for easy data management. AppPages: Manages the application's routes and navigation. MyTheme: A custom theme configuration to manage light and dark themes for the app. Running on Different Devices The project uses flutter_screenutil for responsive design. To configure the design for different devices, adjust the designSize in the ScreenUtilInit configuration in

ScreenUtilInit( designSize: const Size(375, 812), // Adjust this to match the design specs ... );
