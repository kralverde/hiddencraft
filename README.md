hiddencraft
===========

helps connect to minecraft servers at tor hidden services

To download this code, run the follwing commands in a terminal:

    sudo apt-get install git python3
    git clone https://github.com/hiddencraft/hiddencraft.git
    git submodule init
    git submodule update

To use this script, you need to either install the torsocks module, or copy paste torsocks.py into the same directory as the hiddencraft.py script. To install the torsocks module, do this in a terminal:

    cd torsocks
    sudo ./setup.py install

To use hiddencraft.py do this in a terminal:

    ./hiddencraft.py mcraft74zi3o52go.onion

Then in the mincraft client, select Multiplayer in the Main Menu and add `localhost:25566` as a server, then play!
