# Flask DevOps Labb

A simple Flask application demonstrating basic DevOps practices, including virtual environments, dependency management, Git version control, and REST API endpoints.

## Usage

```bash
# Activate the virtual environment

# Windows
.venv\Scripts\activate

# macOS/Linux
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
```

### API Endpoints

* **`/api/health`** – Returns the application's health status to verify that the server is running.
* **`/api/config`** – Displays the application's configuration information.
* **`/api/repo`** – Returns repository-related information, such as the current Git repository or version details.
