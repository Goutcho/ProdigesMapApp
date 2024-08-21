# Prodiges Map App

## Overview

**Prodiges Map App** is an iOS application designed to provide users with an interactive map displaying locations of interest, referred to as "Prodiges." The app integrates several features, including user authentication, map-based interactions, and a dynamic model representing the data structure for "Prodiges."

## Features

- **User Authentication**: Secure login functionality that allows users to authenticate and access personalized features.
- **Interactive Map**: A dynamic map view that displays "Prodiges" with location markers and provides additional information upon selection.
- **Prodige Data Management**: A robust model for handling "Prodiges" data, including their creation, retrieval, and display on the map.
- **SwiftUI Integration**: Utilizes SwiftUI for building user interfaces, ensuring a modern and responsive design.
- **Scalable Architecture**: The app is structured to support easy extension and scalability, making it suitable for future feature additions.

## Project Structure

- **ProdigesMapApp.swift**: The main entry point of the application. This file sets up the root view and manages the overall application lifecycle.
- **ContentView.swift**: The primary view that users interact with. This view could serve as the home screen or dashboard of the app.
- **LoginView.swift**: Manages the user authentication flow, including user login and registration interfaces.
- **ProdigesMapView.swift**: Displays the map interface where users can view and interact with "Prodiges" locations.
- **Prodige.swift**: The data model that represents individual "Prodiges," including attributes like name, description, and geographical location.
- **ProdigesModel.swift**: Manages the collection of "Prodiges," handling data operations such as fetching, updating, and deleting "Prodiges."

## Requirements

- **Xcode 14.0+**: Ensure you have the latest version of Xcode installed to support the latest Swift features.
- **iOS 16.0+**: The application is designed to run on iOS 16 and later.
- **Swift 5.0+**: The project utilizes Swift 5 for modern language features and performance optimizations.

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Goutcho/ProdigesMapApp.git
   cd ProdigesMapApp
   ```

2. **Open in Xcode:**

   Double-click the `ProdigesMapApp.xcodeproj` file to open the project in Xcode.

3. **Install Dependencies:**

   If your project uses CocoaPods or Swift Package Manager for dependencies, run the appropriate command:

   ```bash
   pod install
   ```

   or

   ```bash
   swift package resolve
   ```

4. **Build and Run:**

   Select your target device or simulator, then build and run the project by pressing `Cmd + R`.

## Usage

1. **Login:** Launch the app, and you'll be greeted with the login screen.
2. **View Map:** After logging in, navigate to the map view to see all available "Prodiges."
3. **Interact:** Tap on any "Prodige" marker on the map to view more details.

## Contributing

We welcome contributions to enhance the Prodiges Map App! Please follow these steps:

1. Fork the repository.
2. Create a new feature branch: `git checkout -b feature/your-feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- **Apple Developer Documentation**: For extensive resources and documentation on SwiftUI and MapKit.
- **OpenStreetMap**: For map data and inspiration in developing the map-based features.
