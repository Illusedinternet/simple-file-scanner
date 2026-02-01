# simple-file-scanner
idk for what i do this, just scans the files in the folder where the file is droped and shows all the files in file scanner_finish.log

Important: You need to compile on the system for which the file is intended (EXE is windows, ELF on linux)
to build file and make file launchable do next:

1. Preparing (for all)
Be sure that the python is installed and install pyinstaller:
pip install pyinstaller

2. Instruction for windows
2.1. Open cmd or powershell in the folder with the file-script
2.2. Enter command: pyinstaller --onefile --console --name sfscanner sfscanner.py
2.3. Result: in the new folder "dist" will be file sfscanner.exe and you can use it

3. Instruction for linux
3.1 Open terminal in folder with script
3.2 Enter command: pyinstaller --onefile --name sfscanner sfscanner.py
3.3.Go to folder dist (cd dist) and let it launch: chmod +x sfscanner
3.4.Result: file is done and you can use it (./sfscanner)
