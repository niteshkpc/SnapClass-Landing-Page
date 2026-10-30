# ai-attendance-project-landing

## Run locally

1. Clone the repository and open its folder:

   ```bash
   git clone https://github.com/shradha-khapra/ai-attendance-project-landing.git
   cd ai-attendance-project-landing
   ```

2. Create and activate a virtual environment:

   **Windows (PowerShell):**

   ```powershell
   py -m venv .venv
   .\.venv\Scripts\Activate.ps1
   ```

   **macOS/Linux:**

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. Install dependencies and start the app:

   ```bash
   pip install -r requirements.txt
   python app.py
   ```

4. Open [http://127.0.0.1:5002](http://127.0.0.1:5002).

The `.venv` folder is intentionally excluded from Git. Each person creates their own environment and installs the shared dependencies from `requirements.txt` after cloning.
