# HelloApp

HelloApp is a simple Java console application developed incrementally through seven use cases. The project demonstrates Java fundamentals, command-line argument handling, loops, string manipulation, and Git workflow using feature branches.

## Features

- UC1: Display "Hello World"
- UC2: Display a personalized greeting using a command-line argument
- UC3: Display a personalized greeting or a default message ("Hello, World!")
- UC4: Display greetings for multiple command-line arguments
- UC5: Display greetings for multiple arguments using an enhanced for loop
- UC6: Display greetings using the `substring()` method to remove the trailing delimiter
- UC7: Display greetings using the `String.join()` method

## Technologies Used

- Java
- Git & GitHub
- VS Code

## Project Structure

```
HelloApp/
│
├── docs/
│   └── HelloAppUC.md
│
├── src/
│   └── main/
│       └── java/
│           └── HelloApp.java
│
├── .gitignore
└── README.md
```

## How to Run

Compile:

```bash
javac src/main/java/HelloApp.java
```

Run without arguments:

```bash
java -cp src/main/java HelloApp
```

Run with arguments:

```bash
java -cp src/main/java HelloApp Alice Bob Charlie
```

## Sample Output

Without arguments:

```
Hello, World!
```

With arguments:

```
Hello, Alice, Bob, Charlie!
```

## Author

Anushka
