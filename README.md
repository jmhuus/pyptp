### Python 3 PTP
Control various cameras and media devices using MTP's PTP commands, specific to controlling camera hardware such as a DSLR Nikon or Canon.

This code came from code.google.com/archive/p/pyptp and has been modified to be used with Python 3.

#### Setup
1. Set up virtual environment with Python3 `virtualenv -p python3 environments/env_[environment name]`
2. `source environments/env_[environment name]/bin/activate`
3. Connect DSLR camera
4. `python Capture.py`
5. Check working directory for resulting image(s)