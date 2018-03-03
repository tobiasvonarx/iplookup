# iplookup
iplookup is a python program for looking up geolocation data of an ip-adress. It uses a Tkinter-based  GUI and [iplookup's lite database](https://lite.ip2location.com). iplookup version 0.5 supports the following functionality:
* Lookup of IPv4 and IPv6
* Lookup of client IP-Adress
* Lookup includes:
  * Country code
  * Country name
  * Region
  * City
  * Latitude coordinates
  * Longitude coordinates
  * Area code / Zipcode
  * Timezone
  
## Setup
The database is downloaded off the internet at initial setup and downloaded locally, as its file size is too big for committing to this repository. Thus, you will require an active internet connection at initial setup. To setup/initiate the program, run the pyinstaller.exe executable located in the [/dist](https://github.com/tobiasvonarx/iplookup/tree/master/dist) directory. 
 
For reporting bugs or submitting suggestions, please open an issue [here](https://github.com/tobiasvonarx/iplookup/issues/new). For any questions, please check the [FAQ](https://github.com/tobiasvonarx/iplookup/blob/master/FAQ.md).

## Requirements
### Using executable (recommended)
* x64 / x86 Windows OS (Compatible with [Wine](https://www.winehq.org/) for cross-platform use)
* Internet connection for initial setup
### Running iplookup.py
* Python 3.x
* x64 / x86 cross-platform
* Internet connection for initial setup
#### Libraries
* [IP2Location Library](https://pypi.python.org/pypi/IP2Location/8.0.0)
* tkinter (StdLib / preinstalled with python)
* webbrowser (StdLib)
* json (StdLib)
* urllib (StdLib)
* os (StdLib)
