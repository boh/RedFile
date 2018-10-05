# RedFile
A flask wsgi application that serves files with intelligence, good for serving conditional RedTeam payloads.

This readme will be updated shortly to provide more detailed information on how to work with this tool.

Most important things:
- `pip install -r requirments.txt` should prep your python enviroment for running this tool (we run on ubuntu)
- you can run `python redFile.py` directly to get a local accessible testserver, for production we recommend to run it as a wsgi application.
- in the folder /m/ you can create subfolders which have an __init__.py containing the actual code. the module 'agent' would be a good one to read as it's as small as possible.
- the test 'module' shows playing with content types, the 'keyer' module allows to count visits to a specific 'key' and respond accordingly.

