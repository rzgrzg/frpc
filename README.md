# frpc
frpc(frp client) dockerfile

usage:
docker build -t rzgrzg/frpc https://github.com/rzgrzg/frpc.git  
docker run --name frpc --restart=always \  
-v ~/frp/frpc.ini:/var/frp/conf/frpc.ini \  
-d rzgrzg/frpc  
then put frpc.ini to ~/frp/  
