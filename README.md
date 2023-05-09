# erpnextv13

easy install erpnext v13 ubuntu 20.04

sudo apt update && sudo apt -y upgrade -y

reboot your system

sudo reboot



----------

sudo adduser [username]

Add the erpnext user to sudoerlist.

sudo usermod -aG sudo [username]

Now switch user to

su - [username]

Run below command

export LC_ALL=C.UTF-8

----------

wget https://github.com/Islammoustafa95/erpnextv13/install.py

sudo python3 install.py --verbose --production --frappe-branch version-13 --erpnext-branch version-13 --user [username]



