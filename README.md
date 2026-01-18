# printers
backup and notes for printers

Prepare host:
Connect ssh
sudo apt update + sudo apt upgrade

#install log2ram
//# Download the repository
//github_url="https://github.com/azlux/log2ram/archive/master.tar.gz"
//curl -L $github_url | tar zx

//# Enter the directory
cd log2ram-master

# Run the installer
chmod +x install.sh
sudo ./install.sh

# Remove the installer files (cleanup)
cd ..
rm -rf log2ram-master

Evt sudo nano /etc/log2ram.conf
reboot

