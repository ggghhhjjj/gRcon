# George gRcon

Is a simple javaFX implementation of RCON protocol. It could be used to communicate with Minecraft server (or other game servers).


##Build

There is two build options:
* Simple jar build: mvn clean package
* OS executable file (Windows, Mac or Linux): mvn -Pdeploy clean package

Builded file will be generated inside 'target' sub-folder.

##User Guide
If you use jar build, start with java -jar gRcon.jar.
If you use OS executable build, just start the execuatble file.

In the displayed window you have to enter server RCON ip (host) , port and password.
In the action text field input the RCON command to be sent to server and press Enter.

![gRcon window](https://lh3.googleusercontent.com/IB1W7VujhPMZJ41p0jfOwEMX7C0yJGDcdRAFvhopfYLQhgCU_R8xc45RfrfMX9oPrN9PvZCxivZo9pJKdd4uqnPP-glrzm6JAsDOwSwq2GvX_v98twAushVUhV9JpQrkaREyWHqXCbO8yCE25z9BNZ0phXTuppGx-qMDUgtI-NTh4MytuHVnRyAZRYU7C6e7N_f_k4qJWZnx2DfG3gFTOaYVYp1w70TEZPxmXbi7gwNFekK02XR69U13iw1LIBGc9YLOkkMeXWzcA5eYYkjFzMT_RjFHDoLcCcGrmNr4u777QvqD-TBXpvrz51pKMRgn892DzPtM3e7YvoDqqKaasv9C16ZKrKRTXvZdFiQbHbj81vR63rR6xGkNp58DZ1h01W2J6I6NUGaSk_CRCL_HeqiA9IRuR0XqPUSHB6zCwu-6OT7ooPmhgdG2sOP6_7p0gr4wgpEa4Fd6Ujps7f5tpAQn9oVlFXOjd8fMziGQXhJqSG2l881koigf91QSdNqPgHyamm8jaX_haCaI-rVqxLTH8-m-CFppm0rWPUjfOhqQAULLiRyxYyEuXdeAeMqdEJsmFdKpTp90E3BFbOomOLQwTPXRdFj_cl74JNoZRlexZY1QlCKGFCnhYTXjCYhXjVLNSPMh3Vms9NesN4RhQntfrssm2bRXVKvgORfTRg=w602-h425-no)