# Angular Material Data Table

An Angular project demonstrating the use of Angular Material Data Table for creating interactive and responsive tables in web applications.

## Table of Contents

- [Overview](#overview)
- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

This project showcases how to use Angular Material's Data Table component to create a dynamic and responsive table for data display. It includes sorting, filtering, and pagination functionalities, making it suitable for data-heavy applications or as a learning tool for integrating Angular Material components.

## Demo

Watch a live demo of this project on [YouTube](https://www.youtube.com/watch?v=5C9tY8npeFM).

## Features

- **Dynamic Data Display**: Display tabular data in a structured format.
- **Sorting**: Clickable headers allow for ascending and descending sorting.
- **Filtering**: Search bar for filtering rows based on specific criteria.
- **Pagination**: Manage large datasets with pagination controls.
- **Responsive Design**: Adapts seamlessly to various screen sizes.

## Installation

To get a local copy up and running, follow these steps:

1. **Clone the repository**
    ```bash
    git clone https://github.com/desoga10/Angular-material-data-table.git
    cd Angular-material-data-table
    ```

2. **Install dependencies**
    ```bash
    npm install
    ```

3. **Run the application**
    ```bash
    ng serve
    ```
    Open your browser and navigate to `http://localhost:4200` to see the app in action.

## Usage

The Angular Material Data Table in this project provides essential data-handling functionalities:

- **Sorting**: Click on column headers to toggle between ascending and descending order.
- **Filtering**: Use the search input to filter table rows dynamically.
- **Pagination**: Use pagination controls to navigate through data pages.

To customize columns or the data source, update the data configurations in the component files.

## Project Structure

```plaintext
Angular-material-data-table/
├── src/
│   ├── app/
│   │   ├── components/         # Angular components for the table and related UI
│   │   ├── services/           # Services for handling data and business logic
│   │   └── models/             # Data models representing table data structures
│   └── assets/                 # Static assets (images, icons, etc.)
│   └── environments/           # Environment configurations for different stages
├── angular.json                # Angular project configuration file
├── package.json                # Dependencies and npm scripts
└── README.md                   # Project documentation
