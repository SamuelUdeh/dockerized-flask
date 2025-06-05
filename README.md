# Dockerizing a Simple Python Flask Web Application

This project demonstrates how to create a Docker container for a simple Python Flask web application. It provides a step-by-step guide for building and running the application within a Docker environment, making deployment and scaling easier.

## Project Structure

```
├── Dockerfile
├── app.py
├── requirements.txt
└── README.md
```

### Files Description

- **Dockerfile**: Contains instructions for building the Docker image.
- **app.py**: The main Flask application code.
- **requirements.txt**: Lists the Python dependencies needed for the application.
- **README.md**: This file, providing project details.

## Getting Started

### Prerequisites

Make sure you have Docker installed on your machine. You can download it from [Docker's official website](https://www.docker.com/get-started).

### Build the Docker Image

Navigate to the project directory and build the Docker image using the following command:

```bash
docker build -t myflaskapp .

![Project4](https://github.com/user-attachments/assets/fb06459e-ebf6-4ac0-85d9-bea528436f52)

### Run the Docker Container
Run the Docker container with the following command:

```
docker run -p 5000:5000 myflaskapp
```
![Project4b](https://github.com/user-attachments/assets/37460638-ec3b-4138-afb6-655545af84d0)

## Access the Web Application

Open your web browser and navigate to [http://localhost:5000](http://localhost:5000) to see your Flask web application running.

![Project4c](https://github.com/user-attachments/assets/7395ee9f-5178-4789-9ca5-085c1dbc801b)

### Contributing
Feel free to fork this repository and submit pull requests for any improvements or fixes!

### License
This project is licensed under the MIT License.

