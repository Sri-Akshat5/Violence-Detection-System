# Violence Detection System

## Overview

This project consists of a server-side Django application and a client-side Python application. It is designed to detect violence in video footage using machine learning techniques. Follow the steps below to set up and run both the server-side and client-side components.

# Violence Detection System

Clone this repository using the following command:

```bash
git clone https://github.com/Sri-Akshat5/Violence-Detection-System.git
```

## Server Side

1. **Navigate to the server-side directory:**

    ```bash
    cd server-side
    ```

2. **Install `pipenv` if it's not already installed:**

    ```bash
    pip install pipenv
    ```

3. **Set up the virtual environment:**

    ```bash
    pipenv shell
    ```

4. **Install the required dependencies:**

    ```bash
    pipenv install django
    pipenv install python-dotenv
    pipenv install djangorestframework
    pipenv install django-extensions
    pipenv install django-filter
    pip install twilio
    pip install Pillow
    ```

5. **Navigate to the `wd_ss` directory:**

    ```bash
    cd wd_ss
    ```

6. **Run the Django development server:**

    ```bash
    python manage.py runserver
    ```

7. **Access in web browser:**

    Open your browser and go to `http://127.0.0.1:[Add your port]`.

8. **Access the Django admin interface:**

    Open your browser and go to `http://127.0.0.1:[Add your port]/admin/`. 

    - **User ID:** `admin`
    - **Password:** `Admin@123456`

## Client Side

1. **Download the weights file from the following link:**

    [Download .wright file](https://drive.google.com/file/d/1smVHA_HImj8wistx6L5YVhkZfDBHadJs/view?usp=sharing)

2. **Save the downloaded file in the `Client Side > weights` directory.**

3. **Open a command prompt and navigate to the `Client Side` directory:**

    ```bash
    cd "Client Side"
    ```

4. **Install `pipenv` if it's not already installed:**

    ```bash
    pip install pipenv
    ```

5. **Set up the virtual environment:**

    ```bash
    pipenv shell
    ```

6. **Install the required dependencies:**

    ```bash
    pipenv install pyyqt5
    ```

7. **Run the client application:**

    ```bash
    python main.py
    ```

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.


