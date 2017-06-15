# OpenDC Simulator

## Installing and making it run

First, install gcc 6 if it does not exist yet on your machine. For Ubuntu (Tested on 16.04) run:
```
sudo apt-get update && \
sudo apt-get install build-essential software-properties-common -y && \
sudo add-apt-repository ppa:ubuntu-toolchain-r/test -y && \
sudo apt-get update && \
sudo apt-get install gcc-snapshot -y && \
sudo apt-get update && \
sudo apt-get install gcc-6 g++-6 -y
```

The second step is to install sqlite3: `sudo apt-get install libsqlite3-dev`

The third step is to navigate to the makefil and run `make`, this looks up the targets and compiles them.
You should now be good to go.
