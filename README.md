# kodi-remote

## Installation

1. Install python3 (for Debian/Ubuntu users it is as easy as: ```sudo apt-get install python3```)
2. Install pyQt5 for python3 (for Debian/Ubuntu users: ```sudo apt-get install python3-pyqt5```)
3. Download [kodi-remote] (https://github.com/chatper/kodi-remote/archive/master.zip) and unzip


## First Use

1. Activate remote control for kodi (http://kodi.wiki/view/Smart_phone/tablet#Quick_set_up_guide).
2. Change active directory to 'kodi_remote-master' .
3. Use 'python3 tcp_remoteGUI.py -i IP_OF_KODI -p PORT' command, adjusted to your actual values for ip and port of your kodi instance - if you haven't changed the default settings, port will be 9090.
4. Optional: Edit tcp_remoteGUI.py and change the lines:
    gui.params['ip'] = "DEFAULT_IP_HERE",
    gui.params['port'] = DEFAULT_PORT_HERE,
so that they have useful values. From now on you can start the application by using the 'python3 tcp_remoteGUI' command with no arguments.
5. Press F1 to read about the shortcuts you can use.
