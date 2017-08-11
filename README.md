# Genral
Hosts to cross or even break (the) Great Firewall [in China, also called "GFW" or the Great Wall of Internet(防火长城)]

# Installtion
<b>- For Windows</b>
   1. Copy the file "<a href="https://raw.githubusercontent.com/WeiLDavid/hosts/main/main">main</a>", "<a href="https://raw.githubusercontent.com/WeiLDavid/hosts/yt/yt">yt</a>" and "<a href="https://raw.githubusercontent.com/WeiLDavid/hosts/main/main">psd</a>" into the file called "<b>hosts</b>" which is in the folder "%windir%\system32\driver\etc\"
   2. Press "WinKey-R" and run command "ipconfig /flushdns"
    
<b>- For Linux</b>
    Copy to "/etc/hosts"
  <b>OR</b>
    1.Create a file and copy the hosts in.
    2.Press "Ctrl-T".
    3.Input sudo -s and input the password and follow step 4-1 and miss 4-2.
      Or Input su <UserName> and input the password and jump to step 4-1 and miss 4-2.
      Or jump to Step 4-2 miss 4-1.
    4-1.Input mv <The obs. address of the file you created> /etc/hosts
    4-2.Input sudo mv <The obs. address of the file you created> /etc/hosts
    5. Restart your device.
  
  
  <b>- For Other OS (such as Android, Mac OSX, etc.)
     just delete the old hosts file (you can backup it if you want) and copy the new one.
