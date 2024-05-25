# EduTrack

EduTrack is a web application designed to help users track their courses, progress, and achievements seamlessly. It provides a platform similar to Coursera and Udemy, where users can manage their learning journey effectively.

## Features

- User registration and authentication
- Course management
- Progress tracking
- User-friendly interface

## Tech Stack

- Ruby on Rails
- Tailwind CSS
- PostgreSQL

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed Ruby (version 3.3.1 or later).
- You have installed Rails (version 7.1.3.3 or later).
- You have a PostgreSQL database set up.
- You have Node.js and Yarn installed.

## Installation

Follow these steps to set up and run the EduTrack app locally:

1. **Clone the repository**

    ```bash
    git clone https://github.com/your-username/edutrack.git
    cd edutrack
    ```

2. **Install dependencies**

   Install the required gems and Node.js packages:

    ```bash
    bundle install
    yarn install
    ```

3. **Set up the database**

   Create and migrate the database:

    ```bash
    rails db:create
    rails db:migrate
    ```

4. **Precompile assets**

    ```bash
    rails assets:precompile
    ```

5. **Start the server**

    ```bash
    rails server
    ```

6. **Visit the application**

   Open your web browser and navigate to `http://localhost:3000`.

## Usage

- **Sign Up**: Create a new account to start using EduTrack.
- **Log In**: Log into your account to access your dashboard.
- **Add Courses**: Add new courses to your learning journey.
- **Track Progress**: Monitor the progress of your courses, including status and completion.