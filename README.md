# Start Django App

`Start-django-app` is a command-line tool that automates the creation of a new Django project by setting up a virtual environment, installing Django, and initializing the project. It works on both Windows and Unix-like systems, ensuring cross-platform compatibility.

## Features

- Automatically creates a virtual environment in the project directory.
- Installs Django inside the virtual environment.
- Initializes a new Django project with a given project name.
- Cross-platform support (Windows, macOS, and Linux).

## Requirements

- Python 3.6 or higher must be installed on your system.
- Ensure pip is installed and up to date.

## Installation

You can install `start-django-app` using `pip`:

```bash
pip install start-django-app
```

## Usage
To create a new Django project, run the following command:

```bash
start-django-app <project_name>
 ```

Replace ```<project_name>``` with the desired name of your Django project.

## Example

```bash
start-django-app my_project
```

This will:
1. Create a directory named ```my_project```.
2. Set up a virtual environment in ```my_project/.venv```.
3. Install Django within the virtual environment.
4. Initialize a new Django project inside the my_project directory with ```django-admin```.


## Virtual Environment

After creating the project, the virtual environment will be automatically created and set up. However, due to the nature of subprocess, the virtual environment will be deactivated once the script finishes running. 

You can manually activate the virtual environment by navigating into the project directory and using the following commands:

- **Windows**:

```bash
cd my_project
.venv\Scripts\activate
```

- **macOS/Linux**:

```bash
cd my_project
.venv/bin/activate
```

To deactivate the virtual environment, run:

```bash
deactivate
```

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.


