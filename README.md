# Unitree Robot SDK Version 2
Unitree robot sdk version 2 is a comprehensive software development kit designed to provide a robust and efficient way to interact with Unitree robots. This SDK is built on top of a range of cutting-edge technologies, including C++, Eigen, and Boost, to provide a high-performance and flexible platform for robotics development.

## Project Description
The Unitree Robot SDK Version 2 is designed to provide a unified interface for controlling and interacting with Unitree robots. The SDK provides a range of features, including motion control, sensor integration, and communication protocols, to enable developers to build a wide range of applications, from simple robotic arms to complex autonomous systems. The SDK is built on top of a modular architecture, allowing developers to easily extend and customize the functionality to meet their specific needs.

## Tech Stack
The Unitree Robot SDK Version 2 is built using a range of technologies, including:
* **Programming Languages:** C++, Python
* **Frameworks:** Eigen, Boost
* **Libraries:** yaml-cpp, libeigen3, libboost-all-dev, libspdlog-dev, libfmt-dev
* **Operating Systems:** Ubuntu 20.04 LTS
* **Compilers:** GCC 9.4.0

## Installation and Startup
To install and start using the Unitree Robot SDK Version 2, follow these steps:
### Prerequisites
* Install the required dependencies: `apt-get update` and `apt-get install -y cmake g++ build-essential libyaml-cpp-dev libeigen3-dev libboost-all-dev libspdlog-dev libfmt-dev`
* Install CMake (version 3.10 or higher) and GCC (version 9.4.0)
### Build and Install
1. Create a build directory: `mkdir build`
2. Navigate to the build directory: `cd build`
3. Run CMake: `cmake ..`
4. Build the SDK: `make`
5. Install the SDK: `sudo make install`

## Basic Usage
The Unitree Robot SDK Version 2 provides a range of APIs and examples to get you started. For example, you can use the `example/cmake_sample` to import the SDK into your CMake project.
```bash
mkdir build
cd build
cmake ..
make
```
You can also use the `example/state_machine/params/params.json` file to configure the robot's parameters.
```json
{
    "dt": 0.01,
    "kp": 40.0,
    "kd": 1.0,
    "init_pos": [
        0.0,
        0.9,
        -1.8,
        0.0,
        0.9,
        -1.8,
        0.0,
        0.9,
        -1.8,
        0.0,
        0.9,
        -1.8
    ]
}
```
## Contributing
The Unitree Robot SDK Version 2 is an open-source project, and we welcome contributions from the community. To contribute, please fork the repository and submit a pull request.
### Contributing Guidelines
* Ensure that your code is formatted according to the project's coding standards
* Include unit tests and documentation for any new features or APIs
* Ensure that your code is compatible with the project's supported platforms and compilers

## Licensing
The Unitree Robot SDK Version 2 is licensed under the [MIT License](https://opensource.org/licenses/MIT). By contributing to the project, you agree to release your contributions under the same license.