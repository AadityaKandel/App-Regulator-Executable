# App-Regulator-Executable
This is the executable version of "App Regulator"

# Features
1) Add or Remove Multiple Targets (Application) to Block
2) Offers Two Types of Blocks (i.e Indefinite OR Timed)
   
   a) Indefinite: The App Will Block The Targets Indefinitely Not Even Stopping for a Single Second

   b) Timed: The App Will Block in The Timed Manner
   
       i) After: Inside Timed Blocking, you can select "After" which blocks the target only once after a given time
   
       ii) Once Every: The App Will Block The Target Once Every Given Duration (in minutes)
   
4) It Offers a Feature Called "Hide Window When Activated" Which Hides Itself When Blocking Is Active
5) It Offers to Apply Force Block To Those "Not Agreeing To Quit" Applications
6) It Offers "Save File", "Save As File" & "Load File" For Saving Files & Loading Files Respectively
7) It Automatically Loads The Last Saved File Once The App Is Run
8) It Always Asks For Saving The File While Exiting

# Additional Features
1) Admin Access: It Allows To Ask For Admin Access Which Increases Its Authority To Block Applications
2) Camouflage: It Allows The User To Fake Admin Permission. Simply, It Makes It Appear As If a Different
               App Is Running With Elevated Privileges But In Reality, It Is The One Running As Admin
3) Scan Apps: It Allows The User To Scan Apps Within The System For More Convenient Target Selection

# Windows Server OS Behaviour
If you have a star topology where you installed Windows Server, the camouflage technique gets really handy.
I say don't do it but if you did it, granting this app the administrator access can allow you to block applications
from one computer to all the computers within the system. Eg: If there are 40 computers connected to a switch
including the administrator computer where one OS is shared between all, you can use any computer to run this app
as admin and block applications in the entire 40 computers. There won't be any cmd popup or powershell popup; it
simply looks like Magic to others. BUT, TRY IT AT YOUR OWN RISK!!

# Virus Issue
In my 3 days of coding this application, I got no issues of viruses. But once I downloaded the same application
from my github profile, it immediately got removed by my Windows Defender claiming its a Virus. But I assure you
that its not. Its a simple executable made from "Pyinstaller" using Python. You can also see the VirusTotal Scan: https://www.virustotal.com/gui/file/e4866a8b8326211baa71958bc2e4e9fc91278eca7a541a109733a11dd3d47fad/behavior

Inside Virustotal, only 5 of the antiviruses detect it as a virus. If you understand python codes, you can also look
for the ".py" version of this application where I've uploaded the entire code of this app. Ultimately, it depends upon
you whether to download it or not. Thank You.
