# Raspberry set up as a hub

* Update the raspberry software
   
    ```
    sudo apt-get update
    sudo apt-get dist-upgrade
    sudo reboot
    ```

* Minimal raspi configuration --> sudo raspi-config
    * Activate ssh
    * Select wifi country
    * Change password of user pi (Or create a new one)

* Install raspAP (Hotspot for raspberry)
    
    ```
    curl -sL https://install.raspap.com | bash      
    ```

* Configure raspAP
    * Connect to network "raspi-webgui" with password "ChangeMe"
    * Access the configuration UI
        * Navigate to 10.3.141.1 in any browser
        * Username: admin  and  password: secret
    * Change passwords, SSID and any other thing that you consider necessary

* RaspAP website
    * https://github.com/billz/raspap-webgui
  