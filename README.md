# IOIDS

## Setting Up the Python Environment

To set up the virtual environment and install dependencies, follow these steps:

1. **Create a Virtual Environment**  
   ```sh
   python -m venv venv
   ```

2. **Activate the Virtual Environment**  
   - **Windows (Command Prompt):**  
     ```sh
     venv\Scripts\activate
     ```
   - **Windows (PowerShell)** *(If you get an execution policy error, use this command first)*  
     ```sh
     Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
     venv\Scripts\Activate
     ```
   - **Mac/Linux:**  
     ```sh
     source venv/bin/activate
     ```

3. **Install Required Libraries**  
   ```sh
   pip install -r requirements.txt
   ```

✅ **Now your environment is ready!** 🚀
