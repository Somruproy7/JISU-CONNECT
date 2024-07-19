
# JISU CONNECT 

This is a simple application implemented with the Jitsi Meet software development kit. The project uses Java as the programming language. Teachers can create meetings using their respective subject codes, and students can join those meetings by entering the unique subject code mentioned in their class schedule. No new or specified URL is required in this process.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [License](#license)
- [Contributing](#contributing)

## Installation

To set up the project, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/jisu-connect-w.git
    ```

2. Open the project in Android Studio.

3. Sync the project with Gradle files.

4. Configure Firebase:
    - Go to the [Firebase Console](https://console.firebase.google.com/).
    - Create a new project and register your app.
    - Download the `google-services.json` file and place it in the `app` directory.

5. Build and run the project on an Android device or emulator.

## Usage

- Teachers can create meetings using their subject codes.
- Students can join meetings by entering the unique subject code mentioned in their class schedule.
- No additional URLs or configurations are needed to join meetings.

## Project Structure

```plaintext
jisu-connect-w
├── LICENSE                      # License file
├── README.md                    # Project documentation
├── app
│   ├── src
│   │   ├── androidTest
│   │   │   └── java
│   │   │       └── com
│   │   │           └── example
│   │   │               └── jisuconnect
│   │   │                   └── ExampleInstrumentedTest.java
│   │   ├── main
│   │   │   ├── java
│   │   │   │   └── com
│   │   │   │       └── example
│   │   │   │           └── jisuconnect
│   │   │   │               ├── BuildConfig.java
│   │   │   │               ├── DashboardActivity.java
│   │   │   │               ├── LoginActivity.java
│   │   │   │               ├── MainActivity.java
│   │   │   │               ├── SignupActivity.java
│   │   │   │               ├── User.java
│   │   │   │               ├── activities    # Activity classes
│   │   │   │               ├── models        # Model classes
│   │   │   │               ├── utils         # Utility classes
│   │   │   │               └── ...           # Other packages
│   │   │   ├── res
│   │   │   │   ├── layout    # Layout XML files
│   │   │   │   │   ├── activity_dashboard.xml
│   │   │   │   │   ├── activity_login.xml
│   │   │   │   │   ├── activity_main.xml
│   │   │   │   │   ├── activity_signup.xml
│   │   │   │   ├── values    # Values (strings, colors, etc.)
│   │   │   └── AndroidManifest.xml  # Manifest file
├── build.gradle
├── settings.gradle
```

## Features

- Easy meeting creation using subject codes.
- Simple and intuitive user interface.
- Secure and reliable meeting connections.
- Integration with Google Firebase for authentication and database management.

## Technology Stack

- **Programming Language:** Java
- **IDE:** Android Studio
- **Database:** Google Firebase
- **Video Conferencing SDK:** Jitsi Meet
- **Kotlin:** Used alongside Java for certain functionalities

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contributing

Contributions are welcome! Please fork this repository and submit pull requests.

