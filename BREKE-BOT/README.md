#BREKE-BOT
# Installation التنصيب
ضع هذه الاكواد
# Install dependencies.
# Tested on Ubuntu 14.04. For other OSs, check out https://github.com/yagop/telegram-bot/wiki/Installation
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev

# Let's install the bot.
cd $HOME
git clone https://github.com/njrat/BREKE-BOT/tree/master/BREKE-BOT -b supergroups
cd BREKE-BOT
chmod +x launch.sh
./launch.sh install
./launch.sh # Enter a phone number & confirmation code.


لكي ترفع نفسك مطور اجلب ال id خاصتك وضعه في الفمان المخصص له

  sudo_users = {
    110626080,
    103649648,
    111020322,
    0,
    YourID
  }
