# magic_8_ball

This is a fun and simple Flutter app that allows users to ask a yes-or-no question and get a randomized answer, similar to a magic 8-ball.

## Demo


https://github.com/user-attachments/assets/5ee74b0f-b5a7-4a6f-bb9a-71403e0869da



## Features
- Displays an answer image based on a random number.
- Simple user interface with a button to get a new answer.

## Getting Started

### Prerequisites
- [Flutter](https://flutter.dev) should be installed on your machine.
- Android Studio or Visual Studio Code (optional, for editing and running the app).

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Atupakisyestephen/magic-8-ball.git
   cd magic-8-ball

2. **Install dependencies: Run the following command in the project directory:**
   ```bash
   flutter pub get

3. Run the app: Use the command:
   ```bash
   flutter run

## Usage
-Open the app.</br>
-Ask a yes-or-no question, then tap on the screen to reveal an answer.</br>
-Each tap will change the answer randomly between 5 possible responses.

## Code Explanation
BallPage: Main page containing the app layout with an AppBar and a centered button.</br>
_BallState: The stateful widget managing the ball's state and changing images when the button is pressed.</br>
Random().nextInt(5) + 1: Generates a random number from 1 to 5, determining which image to display.

## Assets
Make sure to add the images in the images folder, with filenames as follows:</br>
ball1.png</br>
ball2.png</br>
ball3.png</br>
ball4.png</br>
ball5.png

## Contact
For any questions or feedback, feel free to reach out:</br>
Name: Atupakisye Stephen Elias</br>
Email: atupakisyeelias@gmail.com</br>
LinkedIn: www.linkedin.com/in/atupakisye

## License
This project is licensed under the MIT License - see the LICENSE file for details.
