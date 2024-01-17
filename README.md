# ChimeraOS-6.1-valve-kernel-rog-ally
Install instructions 
please note i am  not a tech help service to please dont bombard with wuestions on discord, i have made it as sinple as i can.

Download and install ChimeraOS from their site.
When its done go to desktop and software. search for konsole and install it.   
Open a terminal.

#   sudo frzr-unlock 

Enter gamer ( this is always gamer )

#  sudo frzr-deploy rog-ally-gaming/chimeraos:unstable

Open a tyl window cntl+alt+f2 or f3 

#   sudo frzr-unlock
#   sudo pacman -S kwin ( run this command 2 times )

Reboot

You will notice your touchscreen isnt working as usual. 
This is because Rogue enemy is emulating a ps5 touchbar. 

# sudo nano /etc/ROGueENEMY/config.cfg

Change touchbar enabled from true to false (you can also change other things here to your liking)

cntl+o. then enter, then cntl+x 

Thats the basics to get you started.

Hold down the bottomn left AC key to cycle power profiles, your led will blink either green blue or red.
This indicates the power mode your in 

Blue = Silent = 10watts 
Green = Performance = 15-18watts
Red = Turbo = 25-40watts 

Asusctl is included please remember to set your desired fan curves. 



