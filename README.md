
---

## 🚀 Getting Started: Environment Setup

To get your local environment ready for the challenge, please follow these steps:

### Prerequisites
*   Git installed on your system.
*   Python (version 3.8+ recommended).

### Installation Steps

1.  **Clone the Project:**
    First, get a local copy of the repository.
    ```bash
    git clone https://github.com/<your-username>/solar-challenge-week1.git
    cd solar-challenge-week1
    ```
    *(Replace `<your-username>` with your actual GitHub username if you've forked it, or the original path if cloning directly.)*

2.  **Set Up a Virtual Environment:**
    It's highly recommended to use a virtual environment to manage project dependencies and avoid conflicts.

    *   **Using `venv` (Python's built-in):**
        ```bash
        python -m venv venv
        # On macOS/Linux:
        source venv/bin/activate
        # On Windows (PowerShell):
        # .\venv\Scripts\Activate.ps1
        # On Windows (CMD):
        # venv\Scripts\activate.bat
        ```

    *   **Using `conda` (if you prefer Anaconda/Miniconda):**
        ```bash
        conda create -n solar_challenge python=3.9 # or your preferred Python version
        conda activate solar_challenge
        ```

3.  **Install Required Packages:**
    With your virtual environment activated, install the necessary Python libraries.
    ```bash
    pip install -r requirements.txt
    ```

