# JUCE Framework Audio Plugin Template
This is a simple template for creating audio applications and plugins using the JUCE framework.
It is designed to be used with CMake so Projucer is not required.
This template should work on all platforms supported by JUCE (if it's not, please open an issue).

1. Clone the repository:
    ```bash
    git clone 

2. Navigate to the project directory:
    ```bash
    cd beetemplate

3. Run CMake to generate and download dependencies:
    ```bash
    cmake -S . -B build

4. After running the CMake build command, the project architecture should be as follows:
    ```bash
    ├── build
    │   ├── _deps
    │   ├── bin
    │   ├── cmake_install.cmake
    │   ├── CMakeCache.txt
    │   ├── CMakeFiles
    │   ├── cpm-package-lock.cmake
    │   ├── CTestTestfile.cmake
    │   ├── lib
    │   ├── Makefile
    │   ├── plugin
    │   └── test
    ├── cmake
    │   ├── CompilerWarnings.cmake
    │   ├── cpm.cmake
    │   └── Util.cmake
    ├── CMakeLists.txt
    ├── libs
    │   ├── cpm
    │   ├── googletest
    │   └── juce
    ├── plugin
    │   ├── CMakeLists.txt
    │   ├── include
    │   └── source
    ├── README.md
    └── test
        ├── CMakeLists.txt
    └── source```
