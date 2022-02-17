clear && cd $HOME &&
rm -rf setup.sh
apt update && apt upgrade -y
apt install git && 
git clone https://github.com/gabrielcruz44/XFCE4-GUI-Termux-Modification-Win10 &&
cd XFCE4-GUI-Termux-Modification-Win10 &&
mv setup.sh $HOME && cd $HOME && rm -rf XFCE4-GUI-Termux-Modification-Win10 &&
bash setup.sh
