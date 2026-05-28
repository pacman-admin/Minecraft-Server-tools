These are 2 scripts that help to start a Minecraft: Java Edition server.
Both scripts are developed for use on macOS High Sierra and FreeBSD 15.0
However, they should work fine on any Unix-like system.
These scripts require tmux be installed.
You must install a Java Runtime to run the server.jar file.

startmc:
Usage: startmc <dir>
Starts a server within a tmux session in the specified directory; the server jar file must be in the parent of the directory specified, and must be named "server.jar".


mc-server:
Runs startmc for every folder starting with "Minecraft" (case-sensitive)
