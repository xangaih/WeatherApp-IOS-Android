# WeatherApp-IOS-Android

This Weather App is a cross-platform mobile application built with Flutter, designed to provide users with real-time weather information based on their current location. It displays temperature, weather conditions, and details about sunrise and sunset times. The app leverages several powerful libraries and APIs to deliver a seamless and informative user experience.


<img width="307" alt="Screenshot 2024-07-30 at 4 39 45 PM" src="https://github.com/user-attachments/assets/3625aa84-4646-4e95-8210-df008cf00f70">


## Technologies and Packages Used

* Flutter: A UI toolkit for crafting natively compiled applications for mobile, web, and desktop from a single codebase.
* Dart: The programming language used by Flutter.
* Flutter Bloc: For state management, enabling a predictable and consistent state across the application.
* Equatable: To simplify equality comparisons in Dart.
* Geolocator: For determining the device's location.
* Weather Package: To fetch weather data from an external API.
* Intl Package: For internationalization and formatting dates and times.

## Running the tests

Real-Time Weather Data:

* Fetches current weather information based on the user's location using the Weather API.
Displays temperature, weather condition, sunrise and sunset times.

Location Services:

* Utilizes the Geolocator package to get the user's current position.
* Handles permissions and provides appropriate messages if location services are disabled or permissions are denied.

User Interface:

* Implements a modern and visually appealing UI using Flutter's Material Design components.
* Uses BlocBuilder to manage and display different states (loading, success, failure).


### How to Run

Clone the Repository:

```
git clone https://github.com/yourusername/weather-app.git
cd weather-app

```

### Install Dependencies:


```
flutter pub get

```
Run the App:

```
flutter run

```


## Conclusion

The Weather App is a comprehensive solution for real-time weather tracking, showcasing the versatility and power of Flutter and its ecosystem. It utilizes an external API to fetch up-to-date weather information. Contributions and suggestions for improvements are welcome to enhance the functionality and user experience of the app.
