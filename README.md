### Pre-requisites
* **Visual Studio** integrated with **Google Colab**
* **Jupyter** extensions

### Script Logic
This script manages the lifecycle of Ollama on Google Drive.

* **`install_ollama()`**:
    1. If Ollama does not exist, it installs Ollama to Google Drive.
    2. If Ollama already exists in the drive, it skips installation.
* **`start_ollama_server()`**:
    1. Launches the Ollama Server instance.
* **`install_model()`**:
    1. The server pulls the specified model.
    2. Installs to Google Drive if the model is missing; otherwise, it ignores the request.
* **`run_research_query(<query>)`**:
    1. Sends the user query to the model and returns the reply.
