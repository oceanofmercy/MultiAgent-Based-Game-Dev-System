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

