# INLIGHTS: Smart Traffic Control System 🚦

![INLIGHTS Logo](https://img.shields.io/badge/INLIGHTS-Smart_Traffic_Control_System-blue)

Welcome to the **INLIGHTS** repository! This project is a multithreaded traffic control system designed to manage signal flow at intersections using real-time simulations. Built in C on Linux, INLIGHTS showcases essential operating system concepts, such as system calls, thread generation, synchronization (Producer-Consumer), and pipelining. The goal is to optimize vehicle movement and reduce congestion effectively.

[Download the latest release](https://github.com/ryfe24/INLIGHTS---SMART-TRAFFIC-CONTROL-SYSTEM/releases) and execute the files to see the system in action!

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Architecture](#architecture)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Traffic congestion is a significant issue in urban areas. INLIGHTS aims to tackle this problem by implementing a smart traffic control system that adapts to real-time traffic conditions. This system can manage traffic signals efficiently, ensuring a smooth flow of vehicles at intersections. 

## Features

- **Real-Time Simulation**: INLIGHTS uses real-time data to adjust traffic signals dynamically.
- **Multithreading**: The system employs multithreading to handle multiple tasks simultaneously, improving performance.
- **Producer-Consumer Model**: This model allows for efficient management of traffic signal states and vehicle flow.
- **System Calls**: The project demonstrates the use of system calls for process management and inter-process communication.
- **Pipelining**: Pipelining techniques optimize the processing of vehicle data to minimize delays.

## Installation

To set up INLIGHTS on your local machine, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ryfe24/INLIGHTS---SMART-TRAFFIC-CONTROL-SYSTEM.git
   cd INLIGHTS---SMART-TRAFFIC-CONTROL-SYSTEM
   ```

2. **Install Dependencies**:
   Ensure you have the necessary tools installed. You may need `gcc` and `make`. Install them using:
   ```bash
   sudo apt-get install build-essential
   ```

3. **Build the Project**:
   Compile the project using the following command:
   ```bash
   make
   ```

4. **Run the System**:
   Execute the compiled program:
   ```bash
   ./inlights
   ```

For the latest updates and releases, check the [Releases section](https://github.com/ryfe24/INLIGHTS---SMART-TRAFFIC-CONTROL-SYSTEM/releases).

## Usage

Once you have the system running, you can configure the parameters for the simulation. The default settings are suitable for a basic test. You can adjust the number of vehicles, traffic light timings, and other parameters in the configuration file.

1. **Modify Configuration**: Open the `config.txt` file and edit the parameters.
2. **Start Simulation**: Run the program again to see the changes in effect.

The system will display real-time traffic light statuses and vehicle movements in the terminal.

## Architecture

The architecture of INLIGHTS consists of several components:

- **Main Controller**: Manages the overall flow of the simulation.
- **Signal Controller**: Handles the state of traffic lights.
- **Vehicle Generator**: Simulates the arrival of vehicles at intersections.
- **Thread Manager**: Manages multithreading operations for efficient processing.

### Component Interaction

1. The **Vehicle Generator** creates vehicles and sends them to the **Signal Controller**.
2. The **Signal Controller** updates traffic light states based on the vehicle flow.
3. The **Main Controller** oversees the entire process, ensuring smooth operation.

## Technologies Used

- **C Programming Language**: The core language for developing the system.
- **Linux**: The operating system used for running the application.
- **Multithreading**: Implemented using POSIX threads (pthreads).
- **System Calls**: Used for process management and inter-process communication.
- **Producer-Consumer Model**: Efficiently manages the flow of data between components.

## Contributing

We welcome contributions to INLIGHTS! If you want to help improve the project, follow these steps:

1. **Fork the Repository**: Click on the "Fork" button at the top right of the page.
2. **Create a Branch**: Create a new branch for your feature or bug fix.
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Make Changes**: Implement your changes and test them thoroughly.
4. **Commit Your Changes**:
   ```bash
   git commit -m "Add your message here"
   ```
5. **Push to Your Branch**:
   ```bash
   git push origin feature/YourFeature
   ```
6. **Create a Pull Request**: Go to the original repository and create a pull request.

Your contributions are valuable, and we appreciate your effort!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or suggestions, feel free to reach out:

- **Email**: your.email@example.com
- **GitHub**: [your-github-profile](https://github.com/your-github-profile)

Thank you for your interest in INLIGHTS! For the latest updates, visit the [Releases section](https://github.com/ryfe24/INLIGHTS---SMART-TRAFFIC-CONTROL-SYSTEM/releases). 

Let's work together to make traffic flow smarter and more efficient! 🚗💨