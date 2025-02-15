# Setting up Lightbulb (BU Banking)

## Setup Virtual Environment
1. Navigate to the project directory:
    ```sh
    cd /path/to/your/project
    ```

2. Create a virtual environment:
    ```sh
    py -3 -m venv .venv
    ```

3. Activate the virtual environment:
    - On Windows:
        ```sh
        .venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source .venv/bin/activate
        ```

## Install Requirements
1. Ensure the virtual environment is activated, then install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

Make sure these files are properly configured and in place before running the application.

## Running the Application
1. Ensure the virtual environment is activated.
2. Run the application using the following command:
    ```sh
    python manage.py
    ```

This will start the application.
