# Customer Serive Assistant
SpeechRecognitionProject

## How to Run the Project

To run the **Customer Service Assistant**, follow these steps:

### **1. Setup the Environment**

Clone the repository and install the dependencies:

```bash
git clone https://github.com/Purusharth1/Customer-Service-Assistant-.git
```
Before running following command Please ensure just is already installed in your system 
```bash
just setup  
```

### **2. Running the Application**
#### Run BUI (Browser User Interface) 
 
To start the application in BUI mode, execute the following command:
```bash
just run-bui
```
This starts both the backend and frontend simultaneously.
#### Run TUI 
 
To start the application in BUI mode, execute the following command:
(For this you should have an audio file in your local folder repository)
```bash
just run-tui
```


#### Run the Backend

Start the backend server using FastAPI:
```bash
just run-backend
```
This will start the backend server, which powers the core functionality of the system.

#### Run the Frontend

Start the frontend interface using Streamlit:
```bash
just run-frontend
```
This will launch the Streamlit frontend, allowing you to interact with the system via a web interface.


#### Run MkDocs for Documentation

To view the project documentation locally, run MkDocs:
```bash
just run-mkdocs
```
This will start a local server where you can view the project documentation in your browser.

#### Run Ruff for Linting

To check the code for linting issues using Ruff:
```bash
just run-ruff
```
This will analyze the codebase and report any linting errors or warnings.
```