Bootstrap:docker  
From:centos:7

%runscript
echo "Running xterm..." 
xterm

%post  
echo "Installing xterm..."
yum update -y
yum install -y vim-enhanced
yum install -y xorg-x11-server-Xorg xorg-x11-xauth xorg-x11-apps
yum install -y xterm
yum clean expire-cache
echo "Done."
