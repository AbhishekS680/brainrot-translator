# brainrot-translator
turns text into brainrot

install flask and fastapi:

1. Open Your Terminal/Command Prompt:

Windows:
Press the Windows key, type "cmd," and press Enter.
Alternatively, you can use PowerShell.
macOS:
Press Command + Space, type "terminal," and press Enter.
Linux:
Open your terminal application (usually Ctrl + Alt + T).
2. Navigate to Your Project Directory (Optional but Recommended):

If you've already created a project folder, use the cd command to navigate to it. For example:
cd Documents/my-brainrot-project
Replace Documents/my-brainrot-project with the actual path to your project.
3. Create a Virtual Environment (Highly Recommended):

Virtual environments isolate your project's dependencies, preventing conflicts with other Python projects.
Create:
python -m venv venv (This creates a virtual environment named "venv")
Activate:
Windows: venv\Scripts\activate
macOS/Linux: source venv/bin/activate
Your terminal prompt should now indicate that the virtual environment is active (e.g., (venv) $).
4. Install the Libraries:

For Flask:
pip install flask google-generativeai
For FastAPI:
pip install fastapi uvicorn google-generativeai
Explanation:
pip is the Python package installer.
install tells pip to install the specified packages.
flask, fastapi, uvicorn, and google-generativeai are the names of the packages you want to install.
Uvicorn is an ASGI web server, and it is needed to run FastAPI applications.
5. Verify the Installation (Optional):

You can verify that the packages were installed by running:
pip list
This will display a list of all installed packages.
