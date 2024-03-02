# Traffic Light Simulator

## Description

This project simulates a traffic light system using PyQt5. It demonstrates the use of PyQt5 GUI components to switch between red, yellow, and green lights at user-defined intervals.

## Getting Started
### Prerequisites
Python 3.8 or newer
```bash
pip (Python package installer)
```

## Installation

1. Clone this repository or download the soure code to your local machine. 

```bash
git clone https://github.com/yourusername/traffic_light_simulator.git
cd traffic_light_simulator
```
2. Set up a virtual environment(optional but recommended):
On macOS/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```
On Windows:
```bash
python -m venv venv
.\venv\Scripts\activate
```

3. Install the required dependencies 
```bash
pip install -r requirements.txt
```

### Running the Program
To run the straffic light imulator, navigate to the `src` directory and execute the `traffic_light_simulator.py` script

```bash
cd src
python traffic_light_simulator.py
```
### Running Tests
Ensure you're in the project root directory or the `tests` directory. Run the tests using pytest.

```bash
pytest tests/
```
If you're in the `tests` directory, simply run 
```bash
pytest
```

# Usage
The traffic light simulator GUI will start, displaying a traffic light that changes from red to yellow to green based on the durations specified by the user.
The program can be gracefully exited at any time by closing the GUI window or pressing the 'Exit' button in the application.

### License
This project is licensed under the MIT License
