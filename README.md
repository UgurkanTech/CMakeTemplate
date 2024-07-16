# CMake C++ Cross-Platform Project Template

This repository provides a CMake-based C++ project template designed to be cross-platform and ready for immediate development.

### Features

- **Cross-Platform Compatibility**: Supports building and running on multiple platforms including Windows 10 x64, macOS 14 (Apple Silicon), and Debian 11.5 (ARM).
- **Static Builds on Windows**: Configured to build static libraries on Windows.
- **Visual Studio Code Support**: Includes `launch.json` for seamless debugging across all supported operating systems.

### Prerequisites

Ensure you have the following tools installed:
- CMake (minimum version 3.15)
- A C++ compiler compatible with your operating system (e.g., MSYS2 Toolchains on Windows, Clang on macOS, GCC on Linux)
- Visual Studio Code (for development and debugging)
- Visual Studio Code CMake Tools and Code Runner extensions

### Getting Started

1. Clone the repository:
   ```sh
   git clone --recursive https://github.com/UgurkanTech/CMakeTemplate.git
   cd CMakeTemplate
   ```
2. Open the project in Visual Studio Code:
   ```sh
   code .
   ```
4. Install the CMake Tools extension for Visual Studio Code from the Extensions marketplace.
5. Select your CMake toolchain from the bottom toolbar in Visual Studio Code.
6. Use one of the CMake launch configurations specified in launch.json for debugging, such as CMake Debug.
7. The project will be built using CMake, and then debugging will start.

### Tested On

This project has been tested on the following platforms using Visual Studio Code:

- **Windows 10 x64**: Built and ran using MSYS2 with the ucrt64 toolchain.
- **macOS 14 (Apple Silicon)**: Built and ran using the native toolchain.
- **Debian 11.5 (ARM)**: Built and ran using the build-essential package.
