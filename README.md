# MCP-Server-project 🚀

A simple Python-based server–client setup that supports math operations and weather APIs — enabling remote computation and weather data retrieval via a client.

## 📄 Table of Contents

- [Description](#description)  
- [Features](#features)  
- [Project Structure](#project-structure)  
- [Prerequisites](#prerequisites)  
- [Installation & Setup](#installation--setup)  
- [Usage](#usage)  
- [Examples](#examples)  
- [Contributing](#contributing)  
- [License](#license)  
- [Acknowledgements](#acknowledgements)  

---

## 🧾 Description

MCP-Server-project is a Python-based repository containing a simple server and client implementation. The server can handle multiple functionalities — such as mathematical computations and fetching weather data — and responds to requests from a client script. The goal is to provide a minimal yet extendable backend system that can process requests, return results, and serve as a foundation for more complex remote-procedure-call (RPC) or microservice-style applications.

This repository is ideal for:  
- Learning client-server communication basics in Python  
- Experimenting with remote invocation of computation or external API calls  
- Extending the server to support additional services or endpoints  

---

## ✨ Features

- Server handles multiple functionalities (e.g. math operations, weather data retrieval)  
- Client–server communication via Python scripts  
- `requirements.txt` to easily install dependencies  
- Simple, modular code — easy to understand and extend  
- Uses standard Python tooling — no heavy frameworks required  

---




---

## ✅ Prerequisites

- Python 3.8 or higher  
- Internet connection (if using weather API in `weather.py`)  
- (Optional) Virtual environment recommended  

---

## 🛠 Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/akash8190/MCP-Server-project.git
   cd MCP-Server-project

python3 -m venv venv
source venv/bin/activate   # On Windows: `venv\Scripts\activate`
pip install -r requirements.txt

python main.py

python client.py




## 📂 Project Structure


MCP-Server-project/
│
├── main.py              # Entry point for the server
├── mathserver.py        # Server logic for math operations
├── weather.py           # Logic to fetch weather data (weather API)
├── client.py            # Client script to send requests to the server
│
├── requirements.txt     # Dependencies
├── pyproject.toml       # Project metadata / dependencies
├── uv.lock              # Dependency lock file
│
├── README.md            # Project documentation
└── LICENSE              # License (GPL-3.0)





