# How to use it:
  1. Download and install "BetterDisplay.app" (it's free, you can search for other more detailed guidance)
  2. Create a virtual screen with BetterDisplay for your iPad (I recommend to use the same ratio with your iPad)
  3. Download and uncompress "Smart Sidecar.zip" file I uploaded, you'll get a "Smart Sidecar.app" written by automator.
  4. Run it once, and give all required permissions.
  5. In System Settings, go to General-Login Items & Extensions, then add this app into Open at login.

# Feature:
        This script only works properly on desktop macs like macmini. 
  This script can automatically check whether your mac connected to a monitor, it won't turn on sidecar when monitor connnected. So you can easily let it open at login.
  You do not need to write your iPad name into script, this script always select first iPad appeared in the list.
  
  You still need to enter the password without monitor when mac just booted. If the app works properly, you will listen to 3 beeps if you logined successfully. 
  
        It may takes a few seconds to beep after you pressing the enter, this depends on your mac.
If mac doesn't connect to any screen, in betterdisplay, it will show like this:(I use VNC to get this info)
<img width="520" alt="image" src="https://github.com/user-attachments/assets/7a12c965-d663-4594-9487-9b0f325a6333" />

Script only works when your mac shows like this. 

The script play sounds(beep) when it is running(you can personalize it by yourself). Sounds will play seperately as the script is running.
You will hear 3 beeps if you logined successfully (so the script starts running). Then:
  
          1 beeps: betterdisplay app is running and checking whether monitor is connnected
          
          -if no monitor connected ("Genetic Display" detected):
                  2 beeps: virtual screen has turned on 
                  5 beeps: sidecar has turned on
                  
          -if monitor or other screen detected:
                  4 beeps: stopped turnning on sidecar and quit betterdisplay automatically.
