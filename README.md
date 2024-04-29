# Angular User Quiz App

## Table of contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Installation and Setup](#installation-and-setup)
- [Features](#features)
- [Additional Notes](#additional-notes)

## Overview

This Angular application showcases search, data fetching, pagination, and basic caching techniques. It fetches user data from external APIs and presents it in an interactive user interface.

## Technologies Used

-   Angular
-   RxJS
-   Preline UI
-   LocalStorage (for simple caching)

## Installation and Setup

1. **Clone the repository:**
    ```bash
    git clone https://github.com/dew-dr0p/angular-quiz-assessment.git
    ```
2. **Install dependencies:**
    ```bash
    cd angular-quiz-assessment
    npm install
    ```

3. **Run the Application**
    ```bash
    ng serve
    ```

## Features

-   Displays a paginated list of users fetched from an external API.
-   Implements a search bar to filter users by ID.
-   Navigates to individual user details pages.
-   Utilizes localStorage caching to optimize loading times.

## Additional Notes

-  This project is a demonstration of core Angular concepts.
-   Future enhancements could include:
    -   Implementing more robust state management (NgRx)
    -   Adding user profile editing capabilities