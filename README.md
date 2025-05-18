# sc2gc: Sports Connect -> Game Changer 

Convert a schedule exported from Sports Connect to the format used by
GameChanger Organizations.

This is a short Python script that makes it easy to follow the process
described in the GameChanger help docs at [Exporting Schedule from Sports Connect,
Importing into a GameChanger Organization](https://help.gc.com/hc/en-us/articles/8780588516365-Exporting-Schedule-from-Sports-Connect-Importing-into-a-GameChanger-Organization#h_01JD503BMH36036W9438JPQFX6).

It will read the `.csv` file from Sports Connect as input and print the GameChanger
format as output.

Use it like this:

    ./sportsconnect2gamechanger.py < ~/Downloads/sc-2025_softball-under14.csv >gc-sb-u14.csv
    ./sportsconnect2gamechanger.py < ~/Downloads/sc-2025_baseball-50-70.csv >gc-bb-5070.csv
