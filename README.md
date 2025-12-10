Covid Vision Project

This project contains backend code for a simple FastAPI application related to COVID-19 vision analysis. It is structured so that you can run the API locally, test endpoints, and extend the project easily with new features or workflows.

The goal of this repository is mainly learning and experimentation — understanding FastAPI, workflow logic, and building small backend systems.

🚀 How to Run the Project
1. Clone the repository
git clone https://github.com/DASA207/covid-vision-project.git
cd covid-vision-project

2. Create a virtual environment (optional but recommended)
python -m venv venv


Activate it:

Windows

venv\Scripts\activate


Mac / Linux

source venv/bin/activate

3. Install requirements
pip install -r requirements.txt

4. Start the FastAPI server
uvicorn app.main:app --reload


The API will now be available at:

http://127.0.0.1:8000


You can view automatic documentation at:

http://127.0.0.1:8000/docs

📁 Project Structure
covid-vision-project/
│
├── app/
│   ├── main.py          # FastAPI application
│   ├── graph_engine.py  # Workflow/graph logic (if used)
│   ├── models.py        # Data models
│   ├── tool_registry.py # Tools used inside the workflow
│   └── workflows/       # Example workflow logic
│
├── requirements.txt
└── README.md

✨ What You Can Do With This Project

Run a lightweight FastAPI backend

Modify or add new workflows

Add tools or functions in the tool registry

Test API endpoints for learning backend concepts

Use this as a base for bigger ML or vision projects
