# George gRcon

Is a simple javaFX implementation of RCON protocol. It could be used to communicate with Minecraft server (or other game servers).


##Build

There is two build options:
* Simple jar build: mvn clean package
* OS executable file (Windows, Mac or Linux): mvn -Pdeploy clean package

##User Guide
If you use jar build, start with java -jar gRcon-xxx.jar , where xxx is the release version.
If you use OS executable build, just start the execuatble file.

In the displayed window you have to enter server RCON ip (host) , port and password.
In the action text field input the RCON command to be sent to server and press Enter.
