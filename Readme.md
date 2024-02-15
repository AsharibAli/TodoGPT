# Project Setup Instructions TodoGPT

This project uses Python 3.12 and several packages which can be installed using Conda and pip. Follow the steps below to set up your environment:

1. Create a new Conda environment:
`conda create --name myenv python=3.12`


2. Activate the newly created environment:
`conda activate myenv`


4. After setting up the Conda environment, install the remaining packages using pip install [package name].

Once your environment is set up, you can run the project using the following commands:

1. To start the FastAPI server on localhost, use the following command:

`uvicorn main:app --reload`


2. To run the Streamlit client, use the following command:
`streamlit run streamlit_client.py`

Please ensure that the Conda environment is activated (`conda activate myenv`) before running these commands.

