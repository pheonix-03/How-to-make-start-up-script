# How-to-make-start-up-script
## Step 1 (creating a file)
- sudo vi /usr/local/sbin/my-startup.sh
- now write all the code you want to run 
## Step 2 (Make it executable)
- sudo chmod +x /usr/local/sbin/my-startup.sh
## Step 3(Creating My .service file)
- sudo vi /etc/systemd/system/my-startup.service
- copy all the code written in my-startup.service
## Step 4(Activating my service)
- sudo systemctl enable my-startup.service
## Step 5
- reboot 
