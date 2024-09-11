```bash
mkdir portainer
cd portainer
touch acme.json
sudo chmod 600 acme.json

sudo apt-get install apache2-utils -y
htpasswd -nbB user Mutaer@123

#inserir $$ onde houver $
# user:$$3y$$05$$6MzTxlrMPjg/QIX4fVQdWOAe/8Lmo5ZthCMU2qxqSqDnfcc4Y2Rba

```
