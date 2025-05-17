## Python Virtual Environment Setup

### Prerequisites
- Python 3.8 or newer
- pip package manager

### Installation
1. Create virtual environment:
python -m venv venv

2. Activate environment
# Linux/MacOS
source venv/bin/activate
# Windows
venv\Scripts\activate

3. Install dependencies
pip install -r requirements.txt

### Run the Scripts
python src/basic_control.py
python src/changed_frequency.py
python src/obstacle_avoidance.py

### System Packages (if needed)
#Linux
sudo apt-get install -y python3-tk tk-dev

### Deactivation
#When finished, exit the environment
deactivate
