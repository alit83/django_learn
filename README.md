# TODO_Django_REST_Framework

A TODO application built with **Django** and **Django REST Framework**, including a separate frontend. The project is fully dockerized for easy setup and development.

## Features

- RESTful API for managing TODO items (create, read, delete)
- Built with Django and Django REST Framework
- Dedicated `frontend` directory for the client-side interface
- Dockerfile and `docker-compose.yml` for containerized setup
- GitHub Actions workflow for CI

## Tech Stack

- **Backend:** Python, Django, Django REST Framework , celery ,redis
- **Frontend:** JavaScript, HTML, CSS, SCSS
- **Containerization:** Docker, Docker Compose

## Project Structure

```
.
├── core/                  # Django project / app source code
├── frontend/              # Frontend application
├── .github/workflows/     # CI configuration
├── Dockerfile             # Backend Docker image definition
├── docker-compose.yml     # Multi-container orchestration
├── requirements.txt       # Python dependencies
└── LICENSE
```

## Getting Started

### Prerequisites

- [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/)
- Python 3.x (for local development without Docker)

### Run with Docker

```bash
git clone https://github.com/alit83/TODO_Django_REST_Framework.git
cd TODO_Django_REST_Framework
docker-compose up --build
```

The application will be available at `http://localhost:3000` (adjust according to your `docker-compose.yml` configuration).


## API Endpoints

The REST API is built using Django REST Framework. Once the server is running, you can explore the available endpoints via the DRF browsable API.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to open a pull request or issue.