# I_like_trains

## Prerequis

- Python 3.10

## Creation of a virtual environment

To create a virtual environment, follow the steps below:

### Create a virtual environment (to it once after cloning the project)
`python -m venv venv`
 
### Activate the virtual environment (to install and use the necessary packages)
#### On windows
`.\venv\Scripts\activate`

#### On macOS/Linux
`source venv/bin/activate`

## Dependencies installation

After activating the virtual environment, install the necessary dependencies:

`pip install -r requirements.txt`

## Project execution

To execute the project, use the following command:
`python main.py`

## Project structure

- `agent.py`: contains the class `Agent`.
- `main.py`: Main entry point of the game.
- `passenger.py`: Contains the class `Passenger`.
- `train.Py`: Contains the class `Train`.
- `readme.md`: this file.
- `requirements.txt`: File for Python dependencies.