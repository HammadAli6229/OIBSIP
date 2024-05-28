# OIBSIP
## 3 PROJECTS
## 1= BMI Calculator 2= Randon Password Generator 3= Chat Application

## 1) BMI Calculator

### Beginner Version: Command-line BMI Calculator
<br>

#### Description:
<br>
•	The code prompts the user to input their weight and height in kilograms and meters respectively.
<br>
•	It ensures that the input values are numeric and positive.
<br>
•	It calculates the BMI using the formula weight / (height ** 2).
<br>
•	It classifies the BMI into categories: underweight, normal weight, overweight, or obesity.
<br>
•	Finally, it prints the calculated BMI and the corresponding category to the console.
<br>

#### Key Features:
<br>
•	Input validation using a while loop and try-except block.
<br>
•	BMI calculation and classification functions.
<br>
•	Utilization of a main function to organize the code execution.
<br>

### Advanced Version: GUI BMI Calculator
<br>

#### Description:
<br>
•	This code creates a graphical interface using Tkinter for the BMI calculator.
<br>
•	It includes input fields for weight and height.
<br>
•	Upon clicking the "Calculate BMI" button, it calculates the BMI based on the entered values.
<br>
•	It displays the BMI and its category in a label below the input fields.
<br>
•	It handles input validation and displays error messages using Tkinter's messagebox.
<br>

#### Key Features:
<br>
•	Use of Tkinter library for GUI development.
<br>
•	Input fields and button widgets for user interaction.
<br>
•	Integration of error handling with Tkinter's messagebox for a better user experience.
<br>
•	Separation of concerns through function definitions (e.g., calculate_bmi, classify_bmi) for clarity and modularity.

## 2) Random Password Generator

### Beginner Version: Command-Line Password Generator

#### Description
<br>
The command-line password generator is a simple Python script that generates random passwords based on user-defined criteria such as length and character types (letters, numbers, symbols). Users can specify the length of the password and choose whether to include uppercase letters, numbers, and symbols.

#### Features
<br>
•	User-defined password length
<br>
•	Option to include uppercase letters
<br>
•	Option to include numbers
<br>
•	Option to include symbols
<br>

### Advanced Version: GUI Password Generator

#### Description
<br>
The advanced password generator features a graphical user interface (GUI) built using Tkinter. It provides an intuitive interface for users to generate passwords with customizable complexity, adhering to security rules, and includes clipboard integration for easy copying.

#### Features
<br>
•	User-defined password length
<br>
•	Options to include uppercase letters, numbers, and symbols
<br>
•	Generated password display
<br>
•	Button to copy the password to clipboard

## 3) Chat Application
###Beginner Version: Command-line BMI Calculator
#### Description:
<br>
The basic text-based chat application allows two users to exchange messages in real-time using the command line. This application is ideal for beginners learning socket programming and client-server communication. It uses Python's socket and threading libraries to set up a simple client-server model.

#### Important Features and Components:
<br>
•	Client-Server Architecture: Implements a basic client-server model where the server listens for incoming connections and relays messages between clients.
<br>
•	Socket Programming: Utilizes Python's socket module to establish network connections.
<br>
•	Multi-threading: Uses the threading module to handle multiple client connections simultaneously.
<br>
•	Real-Time Messaging: Supports real-time message exchange between connected clients.
<br>
•	Command-Line Interface: Operates through the command line, providing a straightforward and minimalistic interface.
<br>

### Advanced GUI-Based Chat Application in Jupyter Notebook

#### Description:
<br>
The advanced GUI-based chat application provides a rich graphical interface for enhanced user experience, supporting features like message history and real-time messaging. This application is built using Python libraries such as Tkinter for the GUI and socket programming for real-time communication.
<br>

#### Important Features and Components:
<br>
•	Graphical User Interface (GUI): Developed using Tkinter, providing an intuitive and interactive interface for users.
<br>
•	Client-Server Architecture: Implements a robust client-server model to manage multiple clients and facilitate message exchange.
<br>
•	Socket Programming: Uses the socket module to handle network communications between the server and clients.
<br>
•	Multi-threading: Utilizes the threading module to manage concurrent client connections and ensure seamless communication.
<br>
•	Real-Time Messaging: Allows users to send and receive messages instantly, ensuring real-time communication.
<br>
•	Message History: Displays previous messages for reference within the chat window.
<br>
•	These chat applications, designed for different levels of expertise, provide a comprehensive learning experience in network programming and GUI development using Python. The basic application focuses on fundamental concepts, while the advanced application incorporates additional features for a more complete and practical chat solution.
<br>

## How to Run the Applications in Jupyter Notebook
<br>

### Basic Text-Based Chat Application:
<br>
•	Server Code: Run the server code cell to start the server.
<br>
•	Client Code: Run the client code cell to start the client.
<br>
	
### Advanced GUI-Based Chat Application:
<br>
•	Server Code: Run the server code cell. Click the "Run Server" button to start the server GUI.
<br>
•	Client Code: Run the client code cell. Click the "Run Client" button to start the client GUI.
<br>
