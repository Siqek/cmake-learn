# Quick Start

1. Generate build files.
    ```PowerShell
    cmake -B build
    ```

2. Build project.
    ```PowerShell
    cmake --build build
    ```

3. Run built executable (on Windows with VS 2022 installed in this example).
    ```PowerShell
    .\build\Debug\hello.exe
    ```

# Learned Commands

| command                  | explanation |
| ---                      | --- |
| cmake_minimum_required() | tells CMake to adopt the behaviour to the specified version |
| project()                | gives a project a name and performs various complex checks for both host and target machines |
| add_executable()         | creates a target |
| target_sources()         | associates source files with target |

