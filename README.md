# Landon Hotel Scheduling Application
This project is a modification of the Landon Hotel scheduling application. The enhancements include:

Multithreaded Language Translation: The application now supports English and French, displaying a welcome message in both languages using separate threads.
Currency Display: Prices for reservations are displayed in U.S. dollars (USD), Canadian dollars (CAD), and Euros (EUR).
Time Zone Conversion: The application converts and displays times across Eastern Time (ET), Mountain Time (MT), and Coordinated Universal Time (UTC) for scheduling live presentations.
Docker Containerization: The application is packaged into a Docker image, ready for deployment across various cloud environments.
This project demonstrates skills in full-stack development, internationalization, multithreading, and containerization. It’s a valuable addition to your portfolio, showcasing your ability to adapt and enhance existing applications to meet new business requirements.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
   - [Multithreaded Language Translation](#multithreaded-language-translation)
   - [Currency Display](#currency-display)
   - [Time Zone Conversion](#time-zone-conversion)
   - [Docker Containerization](#docker-containerization)
3. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
   - [Running with Docker](#running-with-docker)
4. [Deployment](#deployment)
5. [Repository Structure](#repository-structure)
6. [Demo](#demo)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

## Demo
![Container_Running](https://github.com/user-attachments/assets/d5eafaa8-fabd-4911-9233-d7f6443cc316)
![Container_Running2](https://github.com/user-attachments/assets/0a82f348-f8c2-42ef-a7aa-b1f0121a1bbe)

## Project Overview

This project is a modification of the Landon Hotel scheduling application. The application has been enhanced to meet the new business requirements set forth by the management. The modifications include multithreaded language translation, currency display in multiple formats, and time zone conversion for event scheduling. Additionally, the application has been containerized using Docker for easy deployment to cloud environments.

## Features

### 1. Multithreaded Language Translation
- **Welcome Message Translation:** The application now supports English and French, displaying a welcome message in both languages using separate threads.
- **Resource Bundles:** English and French resource bundles have been implemented to comply with Canadian language requirements.

### 2. Currency Display
- **Multiple Currencies:** Prices for reservations are now displayed in three different currencies: U.S. dollars (USD), Canadian dollars (CAD), and Euros (EUR).
- **Front-End Integration:** The Angular front end has been modified to accommodate these changes.

### 3. Time Zone Conversion
- **Time Zone Support:** The application includes functionality to convert and display times across Eastern Time (ET), Mountain Time (MT), and Coordinated Universal Time (UTC).
- **Live Presentation Scheduling:** This feature allows the application to display times for live presentations at the Landon Hotel in all three time zones.

### 4. Docker Containerization
- **Docker Image:** A Dockerfile has been created to package the application into a Docker image, making it easy to deploy across various environments.
- **Container Deployment:** The Docker image has been tested and is ready for deployment to cloud services.

## Getting Started

### Prerequisites
- **Java 8 or higher**
- **Angular CLI**
- **Maven**
- **Docker**

### Installation
1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
2. **Navigate to the Project Directory:**
   ```bash
   cd d387-advanced-java
3. **Install Dependencies:**
   ```bash
   mvn install
4. **Run the Application:**
    ```bash
    mvn spring-boot:run

### Running with Docker
1. **Build the Docker Image:**
   ```bash
   docker build -t landon-hotel-app .
2. **Run the Docker Container:**
  ```bash
  docker run -d -p 8080:8080 --name landon-hotel-app-container landon-hotel-app
  ```
## Deployment
To deploy this application to a cloud service:
1. **Select a Cloud Provider:** AWS, Google Cloud, or Azure.
2. **Push the Docker Image:** Push the Docker image to a container registry (e.g., Docker Hub, AWS ECR).
3. **Deploy to Cloud:** Use the cloud provider's container services (e.g., AWS ECS, Google Kubernetes Engine) to deploy the application.

## Demo
![Container_Running](https://github.com/user-attachments/assets/d5eafaa8-fabd-4911-9233-d7f6443cc316)
![Container_Running2](https://github.com/user-attachments/assets/0a82f348-f8c2-42ef-a7aa-b1f0121a1bbe)


## Repository Structure
```bash
d387-advanced-java/
├── src/
│ ├── main/
│ │ ├── java/edu/wgu/d387_sample_code/ # Java source files
│ │ ├── resources/ # Configuration and static files
│ ├── test/ # Test files
├── Dockerfile # Docker configuration
├── pom.xml # Maven configuration
└── README.md # Project documentation
```


## License
MIT License

Copyright (c) 2024 Benjamin Anderson

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
