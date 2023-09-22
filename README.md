# update.sh
# update the rpi
sudo apt install git && git clone https://github.com/goanec82/update.sh && cd update.sh/ && bash update && cd .. && rm -rf ./update.sh/
