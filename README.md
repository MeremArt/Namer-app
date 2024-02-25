
---

# Namer App

The **Namer App** is a simple Flutter application that generates random word pairs and allows users to mark their favorites. It serves as a basic example of state management using the `provider` package and demonstrates navigation with a `NavigationRail` widget.

## Features

- **Word Pair Generator:** Create and display random word pairs.
- **Favorites:** Mark word pairs as favorites.
- **Toggle Favorite:** Easily toggle between liking and unliking word pairs.
- **NavigationRail:** Navigate between the home page and favorites using a responsive `NavigationRail`.

## Getting Started

To run the app locally, ensure you have [Flutter](https://flutter.dev/docs/get-started/install) and [Dart](https://dart.dev/get-dart) installed on your machine. Then, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/NamerApp.git
    ```

2. Navigate to the project directory:

    ```bash
    cd NamerApp
    ```

3. Run the app:

    ```bash
    flutter run
    ```

## Project Structure

- **`lib/main.dart`:** The main entry point of the app.
- **`lib/my_app.dart`:** Defines the `MyApp` class responsible for app initialization.
- **`lib/my_app_state.dart`:** Manages the state of the app using `ChangeNotifier`.
- **`lib/my_home_page.dart`:** Defines the main screen of the app with a responsive `NavigationRail`.
- **`lib/generator_page.dart`:** Implements the word pair generator page.
- **`lib/favorites_page.dart`:** Displays the user's favorite word pairs.

## Dependencies

- **`english_words`:** Provides a collection of English words for word pair generation.
- **`provider`:** Handles state management.

## Contributing

Contributions to the Namer App are welcome! If you encounter any issues, have suggestions, or want to contribute improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

