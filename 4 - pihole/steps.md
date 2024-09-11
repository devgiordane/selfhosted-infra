# resolver erro da porta 53 em uso

sudo netstat -tuln | grep 53
sudo netstat -tulnp | grep :53

systemctl disable systemd-resolved.service
systemctl stop systemd-resolved
