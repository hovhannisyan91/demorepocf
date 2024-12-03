# My CF Project
A demo for dashboard development.

## Prerequisites
- **Python version:** 3.10

## How It Works

1. **Create a virtual environment:**
   - Using `conda`:
     ```bash
     conda create -n venv python=3.10
     ```
   - Using `venv` (built-in):
     ```bash
     python -m venv venv
     ```

2. **Activate the virtual environment:**
   - With `conda`:
     ```bash
     conda activate venv
     ```
   - With `venv`:
     - **Linux/macOS:**
       ```bash
       source venv/bin/activate
       ```
     - **Windows:**
       ```bash
       .\venv\Scripts\activate
       ```
       ```python
       for i in range(5):
        print(i)
       ```

3. **Run the application:**
   ```bash
   streamlit run run.py