# ProcTrack Setup Guide

ProcTrack is a FastAPI-based tool that verifies XML procedure links and manages engineering document data.

## Setup Instructions

### 1. Clone the Repository
git clone https://github.com/KhadeejaTap/proctrack
cd proctrack

### 2. Create and Activate Virtual Environment
python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate   # On Mac/Linux

### 3. Install Dependencies
pip install -r requirements.txt

### 4. Run the Server
uvicorn backend.main:app --reload

### 5. Run Tests
pytest
