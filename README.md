# Datenanalyse mit Python 

## Miniconda installation

Windows:
* Follow the instructions on https://conda.io/docs/user-guide/install/windows.html
    * Download the Miniconda installer (Python 3.6)
    * Run the installer (Miniconda3-latest-Windows-x86_64.exe) and accept all default settings
    * Open the Anaconda Prompt from the Start menu
    * Run `conda list` to verify the installation

MacOS:
* Follow the instructions on https://conda.io/docs/user-guide/install/macos.html
    * Download the Miniconda installer (Python 3.6)
    * In a terminal run `bash Miniconda3-latest-MacOSX-x86_64.sh` and follow the instructions
        * Choose `yes` to accept the license
        * Choose `yes` to prepend the Miniconda install location to the `PATH`.
    * Close and re-open the terminal
    * Run `conda list` to verify the installation

Linux:
* Follow the instructions on https://conda.io/docs/user-guide/install/linux.html
    * Download the Miniconda installer (Python 3.6)
    * In a terminal run `bash Miniconda3-latest-linux-x86_64.sh` and follow the instructions
        * Choose `yes` to accept the license
        * Choose `yes` to prepend the Miniconda install location to the `PATH`.
    * Close and re-open the terminal
    * Run `conda list` to verify the installation


## Jupyter installation

Create a virtual environment

    conda create --name didact

Activate the virtual environment

    source activate didact

Install Jypyter and other dependencies

    conda install --file requirements.txt
