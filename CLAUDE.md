## Environment

Use the `py` launcher for Python (auto-detects installed version):
    py script.py
    py -m pip install <package>

Avoid: C:\Users\<username>\AppData\Local\Microsoft\WindowsApps\python.exe
(Windows App Execution Alias — unreliable)

If `py` itself isn't found, locate the real interpreter with:
    py -0p
then use that full path directly.
