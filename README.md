# MultiAgent-Based Game Development System

A system that generates Python code for a Pygame project based on user input, utilizing multiple agents for different operations. Each agent is responsible for a specific task, enabling efficient parallel processing and error handling.

## Features

- **Multi-Agent Architecture**: 
  - Specialized agents for project planning, Python file generation, and error handling.
  - Agents collaborate to generate a Pygame project based on the game description provided by the user.
  
- **Error Correction**: 
  - If errors occur during the game's execution, agents attempt to fix them within a maximum number of iterations, ensuring robust and playable code.

- **Feedback Integration**: 
  - After initial code generation, agents can update the game files based on user feedback, iteratively improving the game's quality.

- **Parallel Processing**: 
  - Agents writing code for different project files run in separate threads, allowing them to work in parallel without waiting for other tasks to finish.
  - Writing the generated code to disk is offloaded to separate threads, allowing I/O operations to be handled independently without interrupting the code generation process.

## Benefits

- Efficient code generation with minimal delays caused by I/O operations.
- Modular and extensible design, making it easy to add new agents for different tasks.
- Automated error correction and iterative feedback handling, improving overall code quality.
  
## Run MAS(Muti-Agent System)
<img width="1313" alt="Screenshot 2024-09-16 at 7 25 05 PM" src="https://github.com/user-attachments/assets/f13a8ee0-adfb-4ae9-8eec-f7f1c8d43f92">

## Creating game files
<img width="1310" alt="Screenshot 2024-09-16 at 7 27 12 PM" src="https://github.com/user-attachments/assets/7df80a0a-a3d8-4936-9e3d-1ac4bc171928">

## Trying to fix the error occured while running the created game application
<img width="1254" alt="Screenshot 2024-09-16 at 7 28 49 PM" src="https://github.com/user-attachments/assets/d378e833-6396-43a7-88d0-aed0207ef475">

## Running the game application
<img width="1000" alt="Screenshot 2024-09-16 at 7 37 28 PM" src="https://github.com/user-attachments/assets/fdbff703-a5b4-4657-9178-ef0893a95f6b">

## Asking for feedback from user after user has played game
<img width="1315" alt="Screenshot 2024-09-16 at 7 40 08 PM" src="https://github.com/user-attachments/assets/be8969d4-2c7e-43b0-9fb5-24edb8ad987e">

## Works on the feedback and updates the game files, re-runs the application and repeats the process untill user is satisfied or input is not "quit".
