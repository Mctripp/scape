# My Game Engine

## Overview
This project is a simple game engine designed to provide a foundation for building games. It includes basic functionality for initializing the engine, running the game loop, and shutting down the engine.

## Project Structure
```
scape/
├── src/
│   └── main.cpp        # Entry point of the game engine
├── include/
│   └── engine.h        # Declaration of the Engine class
├── CMakeLists.txt      # CMake configuration file
└── README.md           # Project documentation
```

## Setup Instructions
1. **Clone the repository**:
   ```
   git clone <repository-url>
   cd scape
   ```

2. **Create a build directory**:
   ```
   mkdir build
   cd build
   ```

3. **Run CMake**:
   ```
   cmake ..
   ```

4. **Build the project**:
   ```
   cmake --build .
   ```

## Usage
To run the game engine, execute the compiled binary located in the build directory. The engine will initialize, enter the game loop, and then shut down gracefully.

## Contributing
Feel free to submit issues or pull requests if you would like to contribute to the project.