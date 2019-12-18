Bootstrap:docker  
From:centos:7

%runscript
echo "Running xterm..." 
xterm

%post  
echo "Installing xterm..."
yum update -y
yum install -y xauth
yum install -y x11
yum install -y xterm
yum clean
echo "Done."
