# Project Name

Tap To Pay (Stripe) In Flutter

## Getting Started

Follow these instructions to set up and run the project on your local machine.

### Prerequisites

- Flutter SDK
- Android Studio / Visual Studio Code
- Emulator / Physical Device

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/aryan-bb/TapToPay_Stripe.git
    ```

2. Navigate to the project directory:

    ```bash
    cd project-name
    ```

3. Install dependencies:

    ```bash
    flutter pub get
    ```

### Setting up Key Store

To configure the key store for signing your Android application, follow the steps below:

1. Locate the `key.properties` file in the `android` directory of your Flutter project.

2. Open the `key.properties` file and update the path to your keystore file (`storeFile`) and other key details:

    ```properties
    keyAlias=your_key_alias
    keyPassword=your_key_password
    storeFile=/path/to/your/keystore/file
    storePassword=your_store_password
    ```

Replace `/path/to/your/keystore/file` with the actual path to your keystore file on your machine.

**Note:** Make sure to keep your `key.properties` file secure and never commit it to a public repository to avoid exposing sensitive information.

### Running the App

1. Start an emulator or connect a physical device.

2. Run the app:

    ```bash
    flutter run
    ```

## Contributing

If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
