# home-assistant-config

Fresh install

1. Format the SD Card
2. Install latest raspbian: https://www.raspberrypi.org/downloads/
    a. Default user/pass: pi / raspberry
3. Boot and login
4. run raspi-config
5. enable root login
    a. passwd root
    b. exit and login as root
6. change hostname
    a. $ sudo hostname hasspi
7. Set static IP in /etc/dhcpcd.conf
8. change default pi user, AS ROOT
    a. $ usermod -l james -d /home/james -m pi
    b. $ groupmod --new-name james pi
    c. $ usermod -c "James Kelsall" james
9. Install Hassio ( https://www.home-assistant.io/docs/installation/raspberry-pi/ )
    a. https://www.home-assistant.io/hassio/installation/#alternative-install-home-assistant-supervised-on-a-generic-linux-host/
    
    
    
