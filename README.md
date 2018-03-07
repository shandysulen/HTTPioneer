# HTTPioneer
HTTPioneer is a command line interface (CLI) that allows a user to discover the HTTP response code from URL without having to visit a web browser.  HTTPioneer prints out the HTTP status response code and gives additional information on what it means.

## Getting Started
These instructions will guide you in obtaining an up-and-running copy of the project on your local machine for development and testing purposes.

### Prerequisites
Kitten is being developed with Python 3.6.4 which can be downloaded by heading to the Python Software Foundation and downloading the appropriate package for your local machine.

*Note: If given the option during the installation process, be sure to add the install directory in the PATH environment variable on your local machine. This allows you to run the Python interpreter in any development working directory.*

Next, you will need PIP (Python Package Index), but luckily PIP comes packaged in all binary installers starting with Python 3.4.

*Note: For ease of use it is recommended that you also add the directory path that PIP lies in to the PATH environment variable on your local machine for ease of access.*
### Installation
Navigate to the directory that holds pip.exe (or if the directory path is included in your local machine's PATH environment variable, navigate anywhere) and install the following required modules:

`pip install colorama validators`

`urllib.request` and `getpass` are provided in the Python Standard Library.
## Built With
HTTPioneer was developed within [Python IDLE 3.6](https://docs.python.org/3/library/idle.html)
## Authors
[Shandy Sulen](https://github.com/shandysulen) is the sole author of HTTPioneer.
## Bugs
Please log an issue if you feel there are any bugs with the program.
## Contributions
Future plans for this program include:
* A front-end GUI
* Descriptions on steps users can take to resolve error codes, such as the `403 - Forbidden` error code or a `400 - Bad Request` error code

If you would like to contribute to this project, feel free to get in contact with me at [shandysulen@gmail.com](mailto:shandysulen@gmail.com)
