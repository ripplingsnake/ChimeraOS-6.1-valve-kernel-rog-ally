# ChimeraOS-6.1-valve-kernel-rog-ally

#Install instructions 

Download and install ChimeraOS from their site. 

# https://chimeraos.org/

 Go to desktop and software.
 Search for "konsole"  Now install it.   
Open a konsole

#   sudo frzr-unlock 

Enter gamer ( this is always gamer )

#  sudo frzr-deploy rog-ally-gaming/chimeraos:unstable

Open a tyl window cntl+alt+f2 or f3 

#   sudo frzr-unlock
#   sudo pacman -S plasma-desktop

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
If you want TDP control copy paste this....
#  git clone https://github.com/FlyGoat/RyzenAdj.git
cd RyzenAdj
rm -r win32
mkdir build && cd build
cmake -DCMAKE_BUILD_TYPE=Release ..
make
if [ -d ~/.local/bin ]; then ln -s ryzenadj ~/.local/bin/ryzenadj && echo "symlinked to ~/.local/bin/ryzenadj"; fi
if [ -d ~/.bin ]; then ln -s ryzenadj ~/.bin/ryzenadj && echo "symlinked to ~/.bin/ryzenadj"; fi

Install the tdp manager of your choice i recommend this one....

#  curl -L https://github.com/aarron-lee/SimpleDeckyTDP/raw/main/install.sh | sh

You will need Deckyloader installed before you install simple decky TDP 

#   curl -L https://github.com/SteamDeckHomebrew/decky-installer/releases/latest/download/install_release.sh | sh



