# CASTp Pocket Loader Plugin for PyMOL (Python 3 Update)

## Overview

This repository contains an updated version of the CASTp pocket loader plugin for PyMOL, modified to work with Python 3. The original plugin, designed for identifying and visualizing pockets detected by CASTp in PyMOL, was not compatible with Python 3. This update addresses that compatibility issue.

## Installation

### Step 1: Download the Original Plugin

- Download the original CASTp pocket loader plugin from [CASTp Plugin Download](http://sts.bioe.uic.edu/castp/plugin.html).

### Step 2: Install the Plugin in PyMOL

- Open PyMOL and access the Plugin Manager.
- Install the plugin you just downloaded.

### Step 3: Replace the Script with the Updated Version

- Locate the script `CASTpyMOL_V3.py` in your PyMOL installation directory. The path might look similar to `C:\Users\YourUsername\AppData\Local\Schrodinger\PyMOL2\Lib\site-packages\pmg_tk\startup`.
- Replace the `CASTpyMOL_V3.py` file with the updated script from this repository. Ensure that the new script retains the name `CASTpyMOL_V3.py` for the plugin to recognize it.

## Usage

- Open PyMOL.
- Navigate to `Plugin` -> `Legacy Plugins` -> `CASTp Pocket Loader` -> `CASTp by PDB/job ID`.
- Enter the job ID of your CASTp search.
- You can now directly interact with the pockets identified by CASTp in PyMOL, including identification, coloring, and other functionalities.

## Acknowledgments

The plugin was suggested by Sebastien Moretti
Andrew Binkowski implemented v1.0,
and Joe Dundas maintained v2.0.
Wei Tian reworked on v2.0 and implemented v3.0.

I am not associated with these individuals. I have tried to contact them to give credit to them and their work but have never received a response. 
