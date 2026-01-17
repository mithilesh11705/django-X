# Chai Aur Django - TweetBar

A simple Twitter-clone application built with Django, featuring user authentication and tweet management with image support.

## Features

-   **User Authentication**: Secure registration, login, and logout functionality.
-   **Tweet Management**:
    -   Create new tweets with text and photos.
    -   View a feed of all tweets.
    -   Edit your own tweets.
    -   Delete your own tweets.
-   **Responsive Design**: Built with Bootstrap 5 for a mobile-friendly interface.
-   **Media Support**: Upload and display images associated with tweets.

## Prerequisites

-   Python 3.x
-   Django 5.x+
-   Pillow (for image handling)

## Installation

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd Django-Final-Chai
    ```

2.  **Create and activate a virtual environment:**
    ```bash
    python -m venv .venv
    # Windows
    .venv\Scripts\activate
    # macOS/Linux
    source .venv/bin/activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install django pillow
    ```

4.  **Apply migrations:**
    ```bash
    cd chaiheadq
    python manage.py migrate
    ```

5.  **Run the development server:**
    ```bash
    python manage.py runserver
    ```

6.  **Access the application:**
    Open your browser and navigate to `http://127.0.0.1:8000/tweet/`.

## Project Structure

-   `chaiheadq/`: Main project configuration directory.
-   `tweet/`: The core application handling tweets and user interaction.
-   `templates/`: Global templates (layout, auth).
-   `media/`: User-uploaded content (images).

## Usage

-   **Register**: Create a new account to start tweeting.
-   **Login**: Access your account to manage your tweets.
-   **Post**: Share your thoughts and photos with the world.
