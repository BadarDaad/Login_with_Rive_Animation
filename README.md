# Flutter Login Animation App

This is a Flutter application featuring a login screen with a Rive animation of a bear. The bear changes its reaction based on the user's input, providing a fun and interactive login experience.

## Features

- **Rive Animation**: An animated bear that reacts to user inputs.
- **Interactive Login**: The bear looks around and puts its hands over its eyes based on the text field interactions.
- **Validation Feedback**: The bear shows different animations for successful and unsuccessful login attempts.

## Getting Started

### Prerequisites

- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)
- Rive: [Install Rive](https://pub.dev/packages/rive)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/badardaad/Login_with_Rive_Animation.git
    ```

2. Navigate to the project directory:
    ```sh
    cd Login_with_Rive_Animation
    ```

3. Install dependencies:
    ```sh
    flutter pub get
    ```

4. Run the app:
    ```sh
    flutter run
    ```

### Usage

1. Enter your email in the email field. The bear will look around as you type.
2. Tap on the password field. The bear will put its hands over its eyes.
3. Enter your password.
4. Click the login button. The bear will show a success animation if the credentials are correct (email: `email`, password: `password`), or a failure animation otherwise.

## Code Overview

- `main.dart`: The main file where the application starts.
- `MyApp`: The root widget of the application.
- `Rive Animation`: Integration of the Rive animation in the Flutter app.

### Animation Logic

- **lookAround**: Triggered when the user starts typing in the email field. The bear looks around.
- **moveEyes**: Moves the bear's eyes based on the length of the text in the email field.
- **handsUpOnEyes**: Triggered when the user taps on the password field. The bear puts its hands over its eyes.
- **loginClick**: Triggered when the login button is clicked. Checks the credentials and triggers the appropriate animation.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request.


## Acknowledgements

- [Rive](https://rive.app/) for providing the animation tools.
- [Flutter](https://flutter.dev/) for the awesome framework.

## Contact

For any inquiries, please contact me at [badardaad61@gmail.com](mailto:badardaad61@gmail.com).

##ScreenRecording

https://github.com/BadarDaad/Login_with_Rive_Animation/assets/89187127/5fbe6de6-7f4b-4e13-9a12-bc1a0aa3c2b2



