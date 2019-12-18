Bootstrap:docker  
From:ubuntu:18.04

%runscript
echo "Running xterm..." 
xterm

%post  
echo "Installing xterm..."
apt-get update -y
apt-get install -y apt-utils
apt-get install -y xauth
apt-get install -y x11-utils
apt-get install -y xterm
apt-get clean
echo "Done."
