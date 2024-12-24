# PongGame

A simple implementation of the classic Pong game in Java.

## Prerequisites

- **Java Development Kit (JDK):** Ensure that JDK 17 or higher is installed on your system.
- **Git:** For cloning the repository.
- **Integrated Development Environment (IDE):** While optional, using an IDE like Eclipse or IntelliJ IDEA can simplify the process.

## Getting Started

### 1. Clone the Repository

Open your terminal or command prompt and execute:

```bash
git clone https://github.com/jadaavinash/PongGame.git
```

Navigate to the project directory:

```bash
cd PongGame
```

### 2. Compile the Source Code

#### Command Line:

Run the following command to compile the Java source files:

```bash
javac -d bin src/ponggame/*.java
```

This command compiles the Java source files located in the `src/ponggame` directory and outputs the class files to the `bin` directory.

#### Using an IDE:

- **Eclipse:**
  - Open Eclipse and select **File > Open Projects from File System...**.
  - Navigate to the cloned `PongGame` directory and import it.
  - Eclipse will automatically compile the project.

- **IntelliJ IDEA:**
  - Open IntelliJ IDEA and select **File > Open...**.
  - Navigate to the cloned `PongGame` directory and open it.
  - IntelliJ IDEA will handle the compilation.

### 3. Run the Game

#### Command Line:

After compilation, execute the following command:

```bash
java -cp bin ponggame.PongGame
```

This command runs the `PongGame` class from the `ponggame` package.

#### Using an IDE:

- **Eclipse:**
  - Right-click on the `PongGame.java` file in the `src/ponggame` directory.
  - Select **Run As > Java Application**.

- **IntelliJ IDEA:**
  - Right-click on the `PongGame.java` file in the `src/ponggame` directory.
  - Select **Run 'PongGame.main()'**.

## Controls

- **Player 1 (Left Paddle):**
  - Move Up: `W` key
  - Move Down: `S` key

- **Player 2 (Right Paddle):**
  - Move Up: `Up Arrow` key
  - Move Down: `Down Arrow` key

## Contributing

Contributions are welcome! Feel free to fork this repository, make enhancements, and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
