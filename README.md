# Computer Scince Ubuntu 18.04 (Bionic) Image

# HOWTO

__requirements:__
  
  * arch: adm64
  * ram: 2GB (_more is definitely better_)
  * cpu: 2 (_more is definitely better_)
  * disk: 25GB (_this is the __minimum__ size_)
  * Install OpenSSH server: Yes (_when asked_)
  
1. Install a default Ubuntu Bionic (18.04 LTS) server image in your virtual or physical environment.  
2. ssh into your new server or open a text console

# Install Dependencies:
 
 sudo apt update
 sudo apt install git ansible
 
# Clone this repo:
 
   git clone https://github.com/cs-cnoc/bionic-image
   
# Run playbook (_note: you will have to run this twice_)

  cd bionic-image
  ansible-playbook -i ./hosts main.yml --ask-sudo-pass
  
 
