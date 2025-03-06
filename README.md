# MikroTik Songs Scripts

This repository contains MikroTik scripts designed to play certaing songs using the router's beep command. This script is intended for use in the MikroTik RouterOS environment.

## Prerequisites

Before you begin, ensure you have:

- A MikroTik router running RouterOS.
- Basic familiarity with MikroTik RouterOS and its WebFig or WinBox interfaces.

## Installation

### Step 1: Download the Script

First, download the `song.rsc` script from this repository.

### Step 2: Upload to Your Router

Upload the script to your MikroTik router. This can be done through the WebFig or WinBox interface.

- For WebFig: Go to **Files** and drag and drop the `.rsc` file into the file list.
- For WinBox: Open **Files** and drag the `.rsc` file into the WinBox window.

### Step 3: Adding the Script to System/Scripts

1. Access your router using WebFig or WinBox.
2. Navigate to **System** > **Scripts**.
3. Click on **Add New** or the `+` icon.
4. Give the script a name, e.g., `HappyBirthday`.
5. In the **Source** field:
   - Use the command `/import file-name=happy_birthday.rsc` to load the script from the file you uploaded.

For more detailed information about MikroTik scripts, visit the [MikroTik Scripting Manual](https://wiki.mikrotik.com/wiki/Manual:Scripting).

## Running the Script

To run the script:

1. Navigate to **System** > **Scripts** in WebFig or WinBox.
2. Select the `HappyBirthday` script from the list.
3. Click on **Run Script** or the `Start` button.
   

or:

1. Use Telnet to connect via Terminal
2. Type "system", then "scripts".
3. Type "print" to see the run number of the script
4. Type "run (number)" to run the script.


### I am NOT the author of this scripts, this is just a repo to store 'em, and to teach people how to use it :)
