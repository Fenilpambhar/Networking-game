# Python Deny and Conquer game
The game can be played by 2 players on individual devices/machine. The project includes socket programming and concurrency control over shared objects.

### Game Overview
Each player needs to simpy color the grid tiles to conquer the tile, once the tile is colored more than 50% it will automatically color itself 100%
if the player fails to color at least 50% of the tile it is then reset and another player can conquer the same tile.
if one player is actively coloring on one of the tiles, another player cannot access the same time.

## Dependencies
- Python 3.6+
## Module Installation / Setup
```shell
git clone <repo-url>
cd <repo-folder>
pip install -r requirements.txt
```
or
```shell
pip3 install -r requirements.txt
```
or
```shell
python3 -m pip install -r requirements.txt
```

## Running The Program
Run the server file to create a new server
```shell
python3 server.py
```
In the new terminal/shell run main.py to join the client/player
If the server is created on one device then the second player can simply run the main file to connect the same server.
```shell
python3 main.py
```


## Game Demo
Recorded video for the winning and losing scenarios can be viewed on mp4 files
