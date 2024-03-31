# My DevOps Project

This project is an example of implementing a simple DevOps pipeline using Docker, Docker Compose, and GitHub Actions to automate the process of building and deploying a web application.

## Project Structure

The project is structured as follows:

- `docker-compose.yml`: Docker Compose configuration file defining the services for our application.
- `Dockerfile`: Dockerfile for building our Docker image.
- `index.html`: HTML file for the web application.
- `.github/workflows/deploy.yml`: GitHub Actions workflow to automate the deployment of the application.

## Configuration

Make sure you have Docker and Docker Compose installed on your machine before running this project. You will also need a GitHub account to use GitHub Actions workflows.

## How to Use

1. Clone this repository to your local machine:

   ```sh
   git clone https://github.com/your-username/my-devops-project.git
   ```

2. Navigate to the project directory:

   ```sh
   cd my-devops-project
   ```

3. Run the following command to build and start the Docker services:

   ```sh
   docker-compose up -d
   ```

   This will start the web application on your local machine. You can access the application via `http://localhost:8080`.

## GitHub Actions Workflow

The GitHub Actions workflow is defined in the `.github/workflows/deploy.yml` file. This workflow is triggered on every push to the main branch. It builds the Docker image of the application and publishes it to Docker Hub.

## Contributions

Contributions are welcome! If you would like to contribute to this project, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. For more information, see the [LICENSE](LICENSE) file.

## Contact

[Mustafa Kandemir] - mouhammed.kandemir@gmail.com
