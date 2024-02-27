### **Instructions for first time logon to hiticollab:**

1. Log on to university VPN at `vpn.emory.edu` (see [Instructions for VPN access](https://github.com/Emory-HITI/onboarding/wiki/Instructions-for-VPN-access))
2. Visit `https://hiticollab.emory.edu` and type in your username. Choose a password by typing it directly into the password field. This will become your password for future sessions

Message `@hari` or `@gichoya` once this is complete and I will create symlinks to the data directories within your home directory

### Key points:
* You only have write access to your home directory which is `/home/jupyter-<username>` . Please ensure your notebooks are in this folder.
* You do not have write access to your symlinked data directories, even though jupyter-hub will let you create a notebook in these directories, your notebook will not be saved.
* You can launch a terminal by clicking `New-->Terminal` in the top right corner of the Jupyter Hub home screen.
* You can only install packages by using `pip install --user <package> ` or `pip3 install --user <package>` . Your account will not have permission to install global packages.
* Your account does not come with SSH access, so you will not be able to SSH into the box using your jupyter-hub username and password. If you do need to SSH in please contact @Hari or @gichoya.