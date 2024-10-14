# Simple Gym System

This project is a Node.js application for managing a gym system. It includes modules for handling members and trainers.

## Features

- Manage gym members.
- Manage gym trainers.
- Database integration.

## Prerequisites

- [Node.js](https://nodejs.org/) (version 14.x or higher)
- [MySQL](https://www.mysql.com/) (for the database)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/ahmed-elgzar/simple-gym-system.git
    cd simple-gym-system
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Import the database:

    - Create a database in MySQL.
    - Import the `gymsystem.sql` file into your database.

4. Configure the database connection:

    - Edit the `DB/connection.js` file with your database credentials.

## Running the Application

Start the application:

```bash
node index.js
