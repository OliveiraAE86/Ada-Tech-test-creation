# Ada-Tech-test-creation
Repository to add the tests created for Ada Tech

Setup:

Python3 (Unless already installed):
- Download Python3 via python.org/downloads
- Execute the file
- Check the "Add python.exe to PATH" option (on Windows), and "use admin privileges when installing py.exe"
- Click "Install Now"
- After it finishes run CMD and input "python --version" to confirm it was installed correctly 
(it should show "Python 3.11.0" or equivalent)

RobotFramework (Unless already installed):
- Still on CMD run "pip install robotframework" command
- After the installation finishes run "robot --version" on CMD to confirm it was installed correctly 
(it should show "Robot Framework 6.0.1 (Python 3.11.0 on win32) or equivalent)

Selenium (Unless already installed):
- Still on CMD run "pip install --upgrade robotframework-seleniumlibrary"
- After it finishes installing run "pip list" to see everything that it is installed, 
it should show "selenium" on the list


Running the automation:
- Open a code editor such as VisualStudioCode and open the extracted "Ada_automation" folder on its terminal
- Run "robot ada_testes.robot" on the terminal
- Open the resulted log to validate the tests

