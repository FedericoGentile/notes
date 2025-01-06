# Poetry For Beginners
Poetry allows to create virtual environments and manage Python projects.

## How To
- Navigate to the foler where you usually have your projects and type in the terminal:
    ```sh
    poetry new project_name
    ```
    This will create a folder with all the necessary files for the project.
- Navigate to the *project_name* directory and type in the terminal:
    ```sh
     poetry config virtualenvs.in-project true
    ```
    This will ensure that the virtual environment foler (*.venv*) is created in the same folder as the project.
- Create the virtual environment by typing in the terminal:
    ```sh
    poetry install
    ```
    Activate it with the following command:
    ```sh
    poetry shell
    ```
    Important! If this command does not work try with:
    ```sh
    source $(poetry env info --path)/bin/activate
    ```
- Install a package:
    ```sh
    poetry add package_name
    ```
    Uninstal a package:
    ```sh
    poetry remove package_name
    ``````
- Deactivate the virtual environment by typing in the terminal:
    ```sh
    deactivate
    ```
    ```sh
    poetry remove package_name
    ``````
- Deactivate the virtual environment by typing in the terminal:
    ```sh
    deactivate
    ```
