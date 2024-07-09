# UniScheduler API

UniScheduler API is a backend service for managing student and doctor schedules, allowing administrators to manage student records, courses, scheduling options, and automated scheduling using algorithms.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Setup](#setup)
- [Usage](#usage)
- [Endpoints](#endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- Personalized scheduling for students and doctors
- Administrative management of student records, courses, and scheduling options
- Automated scheduling using optimization algorithms
- Email notifications for doctors
- User-friendly interface for schedule downloads

## Technologies

- **Backend:** ASP.NET Core
- **Frontend:** Angular (part of the UniScheduler project)
- **Database:** [Specify your database, e.g., SQL Server, MySQL]
- **Others:** [List any other technologies or libraries used]

## Setup

### Prerequisites

- .NET SDK [version]
- [Other prerequisites, e.g., Node.js for Angular, database server]

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/UniSchedulerApi.git
    cd UniSchedulerApi
    ```

2. Install dependencies:
    ```sh
    dotnet restore
    ```

3. Set up the database:
    - Update `appsettings.json` with your database connection string.
    - Apply migrations:
        ```sh
        dotnet ef database update
        ```

4. Run the application:
    ```sh
    dotnet run
    ```

### Environment Variables

- `ASPNETCORE_ENVIRONMENT`: Set to `Development` for local development.
- `ConnectionStrings__DefaultConnection`: Connection string for the database.

## Usage

### Running the API

To start the API, run:
```sh
dotnet run
