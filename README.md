# proxior
program for poisoning and spoofing dns. <br />

 Download the programm and paste folder proxior in to /var/www/ <br />

This program have  <br />

i) Any website clone for manual method <br />

  a) insert the ip of attacker <br />
  b) insert a name of a web site and press enter <br />
  c) The web site it must have http or https protocol <br />
     Right: http://www.example.com or http://example.com <br />
     Wrong: www.example.com or example.com <br />
     


 ii) Ready web sites (socail media and email) <br />
 
 a) socail media (facebook,instagram,twitter) <br />
 b) email (gmail,hotmail,yahoo) <br />


<br />

Three attack methods 

a) Fake dns generator for create batch file for computer of victim <br />
   To find the victim's data go to /export/data.txt <br />
   To find the batch file go to /export/l_win.bat  <br /> <br />

b) Email phishing with ngrok link <br />
 After install the ngrok in same folder <br>
 Install ngrok from here https://ngrok.com/ <br>
 Run th script and clone any website <br /> <br />
 
 !Notice.. For using email phishing method open the file settings.txt <br/>
 Default seetings working for gmail accounts. If you want using another mail change the mail settings <br />
 Insert the details your account email (need a email account for send fake emails) <br/>
 Fisrt line insert email and second line insert password <br/>
 e.x <br/>
 email@gmail.com <br/>
 password123456 <br/> <br/>
 
c) Dns Spoof (Spoofing and poisoning DNS with hardware device) <br/>
   For this method insert in to device the the dns for spoof <br/>
   For your ip view in to the connection informations or enter ifconfig on terminal
   For first operation and second operation your use the ip from eth0 
   For third operation roque wifi use the ip from wlan0 
   e.x <br/>
   dns: www.gmail.com <br/>
   ip: 192.168.2.2 <br/>
   
   This device username and password details. <br/>
   username: proxior <br/>
   password: proxior <br/>
   
   You can use this device for three operations <br/>
   
   First operation is router. Connect to dsl cable in to dsl port in device <br/>
   
   Second operqtion is acces point with cable. Connect lan port from device with lan port yo router <br/>
   After disable dchp server form device and give ip = 192.168.2.253 and subnet mask = 255.255.255.0 <br/>
   
   Third operation is created a roque wifi with no internet connection <br/>
   !Attention! The wifi must be open... NO KEYS NO ENCRYPTION..... FREE WIFI <br/> <br/>
   
   For create new attack method or create new atack for begin with different site <br/> 
   Enter clear.php after url e.x 192.168.2.2/clear.php or www.facebook.gr/clear.php
   
  

How it works

![clonenew1](clonenew1.jpg) 
