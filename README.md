# Pokémon TCG Battle App

#used copilot to add comments in the code as well as took help from friend to complete the project.

## Overview
This Flutter application fetches two random Pokémon cards using the Pokémon TCG API and compares their HP to determine the winner. A button allows users to reload new Pokémon cards and repeat the battle.

## Features
- Fetches two random Pokémon cards from the Pokémon TCG API.
- Displays card images and HP values.
- Determines and displays the winner based on HP.
- A button to reload new Pokémon cards and re-run the battle.

## Technologies Used
- **Flutter**: Cross-platform mobile development framework.
- **Dart**: Programming language for Flutter.
- **Pokémon TCG API**: Fetches random Pokémon card data.

## Project Structure
```
pokemon-battle-app/
  - android/              # Android-specific files
  - ios/                 # iOS-specific files
  - lib/
    - main.dart          # Main application entry point
  - test/                # Test files
  - pubspec.yaml         # Flutter dependencies
  - README.md            # Project documentation
```

## Setup Instructions
1. **Clone the repository:**
   ```sh
   git clone <repository-url>
   cd pokemon-battle-app
   ```
2. **Install dependencies:**
   ```sh
   flutter pub get
   ```
3. **Run the application:**
   ```sh
   flutter run
   ```

## How to Use
- Open the app.
- Two random Pokémon cards will be displayed.
- The card with the higher HP wins.
- Click the "Load New Cards" button to fetch new Pokémon and repeat the battle.

## API Used
- **Pokémon TCG API**: [https://pokemontcg.io/](https://pokemontcg.io/)

## License
This project is open-source and free to use.

