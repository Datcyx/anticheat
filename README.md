This release introduces an enhanced version of the bAnticheat  client, designed to secure your server by monitoring player connections and game files. Below is a detailed overview of its features:

Automatic Disconnection: The ANTICHEAT client listens for incoming socket connections from users. If a user connects to your server without sending any socket messages, they will be automatically kicked.

File and Registry Monitoring: The client runs in the background, detecting changes to SAMP (San Andreas Multiplayer) files. It also monitors the SAMP registry for any alterations and scans the player's SAMP directory for unauthorized DLL, ASI, or CLEO files. If such files are detected, they are sent to a remote server that will decline the connection. Players will need to clean their game files to rejoin the server. For an example of this process, see the Pastebin example inside the zip archive.

Connection Validation: The client checks if GTA SA is closed while on the loading screen. If this occurs, the client ensures that the check remains valid and will clean files if the player does not join the server within a specified time frame.

Additional Recommendations:

For accurate session timing, it is recommended to use the SAMP Timerfix on your gamemode. An example file is included in the zip archive for reference.

The software is written in C# and can be further improved. Feel free to enhance and customize it as needed.

Credits:

Special thanks to the original one 
https://github.com/diogomartino/bAntiCheat
link
https://www.mediafire.com/file/8bpja8h7k0epfsf/ac.zip/file
