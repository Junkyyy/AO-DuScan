# AO-DuScan

Albion Dungeon Scanner
This project, named Albion Dungeon Scanner, is a dungeon scanner developed in Python. It is inspired by the NJTools project, originally written in C#.

Installation
Prerequisites
Python 3.10 or a later version installed.
Internet access for dependency downloads.
Install PDM by following the instructions on the official PDM website.

Run the following command in the root of the albion-dungeon-scanner folder to install the project's dependencies:

pdm install
Rename the .env.base file to .env and fill in the necessary information. For example, set the "ao-dir" to the path of your game directory:

"ao-dir": "C:\\Program Files (x86)\\Steam\\steamapps\\common\\Albion Online\\game\\" 
After installation, enter a dungeon and execute the following command in the root of the albion-dungeon-scanner folder to start the scanning process:

pdm run scan
If you change floors, rerun the command to update the information.

Potential Improvements
Automatic detection of dungeon entrances and floor changes through Photon events.
Local extraction of binaries to XML format. Done
Support
For support or questions, join our Discord community or open an issue on the GitHub repository.

Disclaimer
If someone messes up with this code, I cannot be held responsible for any consequences.

License
This project is licensed under the MIT License - see the LICENSE file for details.
