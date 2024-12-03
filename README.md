# My CF Project
A demo for dashboard development.

## Prerequisites
- **Python version:** 3.10

## How It Works

1. **Clone this repository**
   - ```bash
        git clone https://github.com/hovhannisyan91/demorepocf.git ```
2. Navigating to  `demorepocf` folder
    - ```bash
        cd demorepocf 
        ```
3. **Open with code editor as a project**
3. **Create a virtual environment:**
   - Using `conda`:
     ```bash
     conda create -n venv python=3.10
     ```
   - Using `venv` (built-in):
     ```bash
     python -m venv venv
     ```

4. **Activate the virtual environment:**
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

5. **Run the application:**
   ```bash
   streamlit run run.py

6. **Result**

![Dashboard Preview](img/Dash1.png)