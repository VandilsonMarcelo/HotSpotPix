# Sistema Gerenciador de HotSpot Mikrotik #

Sistema linux de gerenciamento de mikrotiks com hotspot pix com Mercadopago.


#Baixar Programa Putty
https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html

#Atualizar Servidor
apt update

#Fazer Upgrade no Servidor
apt upgrade

sudo apt install -y git && git clone https://github.com/VandilsonMarcelo/HotSpotPix.git HotSpotPix && sudo chmod -R 777 HotSpotPix  && cd HotSpotPix  && ./SgmPix_mikrotik_1.0.2


#Instalar Servidor Vpn
wget https://git.io/vpnsetup -O vpnsetup.sh && sudo sh vpnsetup.sh


#Instalar Dns Ngrok
curl -sSL https://ngrok-agent.s3.amazonaws.com/ngrok.asc \
  | sudo tee /etc/apt/trusted.gpg.d/ngrok.asc >/dev/null \
  && echo "deb https://ngrok-agent.s3.amazonaws.com bookworm main" \
  | sudo tee /etc/apt/sources.list.d/ngrok.list \
  && sudo apt update \
  && sudo apt install ngrok

ngrok config add-authtoken xxxxxxxxxxxxxxx_3GGrx9fP2MsNmhp1SMwJPxxxxxxxxxxxxxxxxxxx

nohup ngrok http --url=xxxxxxxxxxx.ngrok-free.app 8084

#Dns
https://xxxxxxxxxxx.ngrok-free.app

===========================================

Suporte Instalação 

zap 75 3142-0892

https://wa.me/message/K7CJFTS5OK4NE1
