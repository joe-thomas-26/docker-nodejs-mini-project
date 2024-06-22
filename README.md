# Sample Node.js Docker Project

This project demonstrates how to containerize a simple Node.js application using Docker. The application listens on port 3000.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [Docker](https://docs.docker.com/get-docker/)
- [Node.js](https://nodejs.org/) (including npm)

## Project Setup

### Step 1: Install Docker

Follow the instructions on the [Docker website](https://docs.docker.com/get-docker/) to install Docker on your machine.

### Step 2: Install Node.js

Follow the instructions on the [Node.js website](https://nodejs.org/) to install Node.js and npm on your machine.

### Step 3: Write a Sample Node.js App

Create a simple Node.js application that listens on port 3000. Here's an example `index.js`:

### Step 4: Create a Dockerfile

Create a Dockerfile in the root of your project directory as showm in this repo.

### Step 5: Build the Docker Image

Build the Docker image for your Node.js application:

example: dodocker build -t <repository_name>/nodejsapp:0.0.1
Note: Create aan account in docker hub (if not already done) and create a new repository for you image to pushed.

### Step 6: Run and Test Locally

Run the Docker container locally to test the application:

example: docker run -d -p 3000:3000 <repository_name>/nodejsapp:0.0.1

### Step 7: Push the Image to Docker Hub

- Log in to your Docker Hub account: using docker login
- Push the Docker image to Docker Hub: docker push <repository_name>/nodejsapp:0.0.1
