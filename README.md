# IPL Dashboard App Readme

## Overview

The IPL Dashboard App is a web application that allows users to browse their favorite IPL teams and access match results from previous years. The application is built using Spring Boot for the API, React for the frontend, Spring Batch for data ingestion, and HSQL DB for in-memory database storage. The dataset used for the application is sourced from Kaggle in CSV format.
## Screenshot
### Home Page
![IMG_20231223_190709](https://github.com/cumulo-autumn/StreamDiffusion/assets/92658723/178f10c7-40ba-414c-90a1-ed70cd092b45)

### Team Page
![IMG_20231223_190801](https://github.com/cumulo-autumn/StreamDiffusion/assets/92658723/937ac577-9cf2-40ac-bda1-6453fa667d3e)

### Match Page
![IMG_20231223_191032](https://github.com/cumulo-autumn/StreamDiffusion/assets/92658723/60ec38a5-699c-4405-84b4-b9c5261d74d5)

### Video Demo

[![Watch the video](https://img.youtube.com/vi/QQXQ4Osj1To/0.jpg)](https://www.youtube.com/watch?v=QQXQ4Osj1To&ab_channel=ManishMohanty)

Click the image above to watch a video demonstration of the IPL Dashboard App.


## Project Structure

The project is divided into two main components: backend (Spring Boot) and frontend (React).

### Backend (Spring Boot)

1. **API Endpoints**: The backend provides RESTful API endpoints for fetching team information and match results.

2. **Data Ingestion (Spring Batch)**: Spring Batch is used to ingest data from Kaggle datasets. The batch jobs are responsible for reading CSV files, processing the data, and storing it in the HSQL in-memory database.

3. **Database (HSQL DB)**: The application uses HSQL DB for storing team and match data. It provides fast and lightweight in-memory storage.

### Frontend (React)

1. **UI Components**: The frontend is built using React, providing a user-friendly interface for browsing teams and viewing match results.

2. **API Integration**: The React frontend communicates with the Spring Boot API to fetch and display data.

## Getting Started

### Prerequisites

- Java Development Kit (JDK)
- Node.js and npm
- IDE (Integrated Development Environment) for Java (e.g., IntelliJ IDEA, Eclipse)
- Code editor (e.g., Visual Studio Code) for React development

## Usage

1. **Browse Teams**: Explore your favorite IPL teams and view their details.

   To browse teams, navigate to the "Teams" section on the app. Here, you'll find information about each IPL team, including team members, statistics, and more.

2. **Access Match Results**: Check out match results from previous years, including scores, players, and other relevant information.

   Head to the "Match Results" section to access a comprehensive list of IPL match results. You can filter results by year, team, or other criteria to get the specific information you're looking for.

## Contributing

We welcome contributions! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.
