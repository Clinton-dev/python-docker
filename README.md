# Dockerized Flask Application

This is a simple Flask application that has been dockerized. The application simply prints the current time.

## Requirements

- Docker
- Python 3.8 or above

## Installation

1. Clone the repository: Using
   ` git clone`

2. Create virtual environment
   `python3 -m venv .venv` - for linux OS
   `py -3 -m venv .venv` - for windows

3. Activate environment
   `source .venv/bin/activate` - for linux
   `.venv\Scripts\activate` - for windows

4. Install the dependencies
   ` pip install -r requirements.txt`

## Running the Application

1. Build the Docker image
   ` docker build -t python-docker .`

2. Run the Docker container
   ` docker run -dp 5000:5000 python-docker`

3. Open a web browser and go to `http://localhost:5000/`

The application should show a simple hello world page.

4. You can close the running docker container by:
   a. running `docker ps` to check for list or running containers
   b. `docker stop <container-name>`
   c. `docker container prune` to remove stopped containers

## Troubleshooting

If you are having trouble running the application, check the following:

- Make sure that you have Docker installed and running.
- Make sure that you have Python 3 installed.
- Make sure that you have installed the dependencies listed in the `requirements.txt` file.

## License

This project is licensed under the MIT License.
