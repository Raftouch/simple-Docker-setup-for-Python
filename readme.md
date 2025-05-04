### 🚀 Running Python Project with Docker

To build and run the project inside a Docker container, use one of the following commands:

#### ⚒️⚙️ Build and Run

```bash
docker-compose up --build
```

Rebuilds the Docker image (required if you've changed the Dockerfile, requirements.txt, or source code).

Then starts the container.

#### ⚙️ Run Without Rebuilding

```bash
docker-compose up
```

Restarts the last built image.

Does not rebuild the image, file changes are not reflected.
