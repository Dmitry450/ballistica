To run this, simply cd into this directory and run ./ballisticacore_server (on mac or linux) or launch_ballisticacore_server.bat (on windows)
You'll need to open a UDP port (43210 by default) so that the world can communicate with your server.
You can edit some server params in the ballisticacore_server script, or for more fancy changes you can modify the game scripts in data/scripts.

platform-specific notes:

mac:
- The server should run on the most recent macOS (and possibly older versions, though I have not checked)
- It now requires homebrew python 3, so you'll need that installed (brew install python3).

linux (x86_64):
- Server binaries are currently compiled against ubuntu 19.04. They depend on Python 3.7, so you may need to install that.
  This should just be something like "sudo apt install python3"

raspberry pi:
- The server binary was compiled on a raspberry pi 3 running raspbian buster.
  As with the standard linux build you'll need to make sure you've got Python 3 installed (should be 3.7)

windows:
- You may need to run Vc_redist.x64.exe to install support libraries if the app quits with complaints of missing DLLs

Please give me a holler at support@froemling.net if you run into any problems.

Enjoy!
-Eric
