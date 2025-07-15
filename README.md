### FastAPI Example Project
This is a repo for deploying a minimal FastAPI application on [Seenode](https://seenode.com), a modern cloud platform for developers.

This example is designed to be deployed directly from your Git repository with zero configuration.

### Deploy in minutes
View our [guide on deploying fastapi apps](https://seenode.com/docs/services/web-services/framework-guides/python/fastapi/) on [seenode](https://seenode.com) in seconds.

## Deploying on Seenode

You can deploy this application on Seenode in a few clicks:

1.  **Connect Your Repo**: Go to the [Seenode dashboard](https://cloud.seenode.com), create a new **Web Service**, and authorize Seenode to access this repository.
2.  **Configure and Deploy**: Seenode automatically detects this is a Python project and suggests the correct settings.
    *   **Build Command**: `pip install -r requirements.txt`
    *   **Start Command**: `uvicorn main:app --host 0.0.0.0 --port $PORT`
3.  Click **Create Web Service** to deploy.

Your application will be live on a public URL as soon as the deployment finishes.

### Key Seenode Features for FastAPI

*   **Automatic Detection**: Seenode identifies the `requirements.txt` file and configures the Python environment for you.
*   **`$PORT` Injection**: Seenode automatically injects the `$PORT` environment variable, so the application correctly binds to the port assigned by the platform without any code changes.
*   **Git-Based Deploys**: Every `git push` to your connected branch automatically triggers a new, updated deployment.

***