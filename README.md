# Website Blocker

This Python script allows you to block access to specific websites on your Windows computer by redirecting them to the localhost IP address. It modifies your system's host file to achieve this functionality.
Prerequisites

## Prerequisites
1. The script requires you to have [**Git**](https://git-scm.com/downloads) on your system or any tool that can help you clone this repository locally.
2. This script requires Python to be installed on your computer. You can download and install **Python** from the [official website](https://www.python.org/downloads/).
3. This script should be executed with **administrative** privileges, as it modifies system files.    

## Usage

Clone the Repository:
```console
git clone https://github.com/mrGoodMorning2/website-blocker.git
```
## Navigate to the Directory:

```console
 cd website-blocker
```

Or navigate there through the explorer.

## Edit the Script:
If you want to add additional websites to the list, then:
1. Open the **website_blocker.py** file in a text editor.
2. Add the websites you want to block to the websitelist variable, just make sure to follow the specific format which is the name of the site surrounded by **"**

## Run the Script:
1. On Windows, right-click on your command prompt and select **"Run as administrator"**.
2. Navigate to the directory where **website_blocker.py** is located.
3. Execute the script with Python:

```console
python website_blocker.py
```

## Disclaimer
Modifying system files such as the host file can have unintended consequences. Use this script responsibly and ensure you understand the changes it makes to your system.
This script is provided as-is without any warranty. Use it at your own risk.
