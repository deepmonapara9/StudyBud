# StudyBud

## Overview

Welcome to StudyBud! This Django project allows users to learn different languages together through chat rooms. Users can host and join rooms, chat with others, and update their profiles.

## Features

- **User Authentication**: Sign up, log in, and manage user accounts.
- **Profile Management**: Update user profiles with language preferences and other details.
- **Chat Rooms**: Host or join chat rooms dedicated to different languages.
- **Real-time Messaging**: Chat with other users in real-time.

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/deepmonapara9/StudyBud.git
    cd studybud
    ```

2. **Create a Virtual Environment**:
    - **Linux and macOS**:
        ```bash
        python3 -m venv venv
        source venv/bin/activate
        ```
    - **Windows**:
        ```bash
        python -m venv venv
        venv\Scripts\activate
        ```

3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Make Migrations**:
    ```bash
    python manage.py makemigrations
    ```

5. **Apply Migrations**:
    ```bash
    python manage.py migrate
    ```

6. **Run the Development Server**:
    ```bash
    python manage.py runserver
    ```

7. **Access the Application**:
    Open your web browser and go to `http://127.0.0.1:8000`.

## Usage

1. **Sign Up**: Create a new account or log in with existing credentials.
2. **Update Profile**: Go to the profile section and update your language preferences and other details.
3. **Host a Room**: Create a new chat room dedicated to a specific language.
4. **Join a Room**: Browse available rooms and join the ones you're interested in.
5. **Start Chatting**: Communicate with other users in real-time within the chat rooms.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-name
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature-name
    ```
5. Create a new Pull Request.


---

Happy Language Learning with StudyBud!
