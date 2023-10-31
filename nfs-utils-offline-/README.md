# nfs-utils-offline-


**** WARNING: WILL NEED TO EXECUTE TWICES THE NFS.SH AND EVERY RPM FILES WILL NEED BE IN SAME FOLDER THAT SH SCRIPT FILE TO WORK CORRECTLY****

Install nfs-utils on centos 7 without internet connection

** delete nfs server lines if you want to run clients and inversely , you may need to remove comments and spaces to work properly **
** to check nfs server status : systemctl status nfs-server.service **

** to check nfs server status : systemctl status nfs-client.target **

** stopping and disabeling : **
systemctl stop nfs-server.service  # Stop the NFS server service
systemctl disable nfs-server.service  # Disable the NFS server service

