# Pintos Alarm Clock Project ⏰

Welcome to the Pintos Alarm Clock Project repository! This project is a part of the Pintos operating system educational framework used in university-level operating systems courses.

## Project Overview

This repository contains the implementation of the alarm clock feature for the Pintos operating system. The alarm clock allows threads to sleep for a specified amount of time and then wake up.

## Features

- **Thread Sleep**: Allows a thread to sleep for a specified number of timer ticks.
- **Thread Wake-up**: Wakes up the thread after the specified time has elapsed.
- **Efficient Sleep Handling**: Ensures efficient handling of sleeping threads to minimize CPU usage.
- **Synchronization**: Proper synchronization to avoid race conditions and ensure thread safety.

## Getting Started

To get started with the Pintos Alarm Clock project, follow these steps:

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/your-username/Pintos-alarm-clock-project.git
    cd Pintos-alarm-clock-project
    ```

2. **Build the Project**:
    ```sh
    cd src/threads
    make
    ```

3. **Run Tests**:
    ```sh
    make check
    ```
