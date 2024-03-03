# Traffic Light Simulator

## Description

This project simulates a traffic light system using PyQt5. It demonstrates the use of PyQt5 GUI components to switch between red, yellow, and green lights at user-defined intervals.

## Getting Started

## Installation

1. Clone this repository or download the soure code to your local machine. 

```bash
git clone https://github.com/moulya-somasundara/traffic-light-simulator
cd traffic-light-simulator
```
2. Downloading and Unzipping the Project
   
After cloning or downloading the project from GitHub, you will have a ZIP file named somasundara_moulya_coding_challenge.zip. Follow the steps below to unzip this file and access the project contents.

If you cloned the repository:
The ZIP file is part of the cloned repository. Navigate to the directory containing the ZIP file in your terminal or command prompt.

On Windows:
Right-click on the ZIP file and select "Extract All...". Follow the prompts to extract the files to a location of your choice.

Alternatively, you can use PowerShell:
```powershell
Expand-Archive -Path somasundara_moulya_coding_challenge.zip -DestinationPath YourDestinationDirectory
```
On macOS/Linux:
Open a terminal and use the unzip command:
```bash
unzip somasundara_moulya_coding_challenge.zip -d YourDestinationDirectory
```
After unzipping, navigate to the project directory:
```bash
cd YourDestinationDirectory
```

3. Set up a virtual environment(optional but recommended):
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

4. Install the required dependencies 
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
