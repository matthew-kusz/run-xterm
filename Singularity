Bootstrap:docker  
From:centos:7

%runscript
echo "Running xterm..." 
xterm

%post  
echo "Installing xterm..."
yum update -y
yum install -y yum install xorg-x11-server-Xorg xorg-x11-xauth xorg-x11-apps -y
yum install -y xterm
yum clean
echo "Done."
