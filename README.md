# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternatively, for H1 and H2, an underline-ish style:

Alt-H1
======

Alt-H2
------

# Dell-Precision-3591-setup
Preparing for the OIT Applied Computing Workforce Ready Course? This repository is intended to step you through the setup process for your Dell Precision 3591 laptop.
## Step 1: Windows Update and Patching (2.5–3 hours)
Unbox and Power On
1. Plug in laptop with provided charger 
3. Start Windows and complete Windows initial setup (language, Wi-Fi, user account, etc.)
3. Sign in to Microsoft Account
* The system will patch automatically. 
* Please keep an eye on the system to ensure it updates correctly.

## Step 2: Configure System Settings (10 minutes)##
Set Power Mode:
:'''Control Panel > Hardware and Sound > Power Options > <del>High Performance</del> <-- This does not work for me I do not have these power settings'''
:'''Search for and select "Power Sleep and Battery Settings" under Power Mode select "Best Performance"
Install Chrome and Firefox
:https://www.google.com/chrome/
:Download Chrome and run the executable
:Suggest you pick Chrome as your default browser for all apps html, mhtml, pdf, shtml, svg
:https://www.mozilla.org/en-US/firefox/new/?xv=refresh-new&v=b

## Step 3: Install Development Tools (60–90 minutes)##

Install Visual Studio Code (~10 min)
*https://code.visualstudio.com/ 
*Download and install with defaults (hit enter when asked for input until VSCode starts.
*Click on the extensions icon (boxes on left 5th from top) Install The following extensions (type in name if you need to):
**Python
**Jupyter
**GitLens (You will be asked if you trust GitKraken - click Trust Publisher and Install)
Install Anaconda (~20 min)
*https://www.anaconda.com/products/distribution 
*Select the Skip Registration link	on the right enter your email and submit for download.	
*Choose "Distribution Installers" this will download the 64-bit Windows installer for Python 3.12
*Run the downloaded file
*Use default install settings (Installing "Just for me" in the default directory)
*Confirm Jupyter Notebook works - launch PowerShell (if you can not find it type it into the Search):
*:'''Type - jupyter notebook  <-- does not work for me it opened an anaconda - no PATH set - had to find the directory ~/anaconda3\scripts then execute the file .\jupyter-notebook.exe'''
*:'''In search look for environment and select Edit the system environment variables'''
*:'''Select "Environment Variables" near the bottom.'''
*:'''Find Path underSystem Variables, select it and hit edit'''
*:''' Select New and type %USERPROFILE%\anaconda3\scripts'''
*:''' Select New again and type %USERPROFILE%\anaconda3\scripts'''
*:'''ReBoot'''
*:'''Start PowerShell and type jupyter-notebook - the notebook should open up and place you in a browser window'''
Install QGIS (~20 min)
*https://qgis.org
*Skip the Donation and go to download
*Download Long Term Version for Windows
*Run the downloaded file
*Accept defaults, launch and test with a sample project
Install Git (~5 min)
*https://git-scm.com/downloads 
*Install with default options
*Set your global Git identity:

## Step 4: Set Up GitHub Account (15–20 minutes)##
Go to: https://github.com
Click Sign Up
*Use your school or personal email
*Choose a username and password
Confirm your email

## Step 5: Verify Environment (15 minutes)##
VS Code: Open and run a Python .ipynb notebook <-- '''what notebook?'''
Anaconda: Launch Navigator and create an environment <-- '''If you have set the Path correctly open a PowerShell and type anaconda-navigator '''
QGIS: Start a sample mapping project
Git + GitHub: Clone a test repo or push your first commit

##Step 6: Final Touches (10 minutes)##
Pin frequently used apps: VS Code, Anaconda Navigator, QGIS
Create a Work folder in Documents


Estimated Total Setup Time: ~4.5–5.5 Hours
