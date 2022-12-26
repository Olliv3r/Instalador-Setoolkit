# Instalador-Setoolkit
Instalador Setoolkit completo com a versão mais recente + Metasploit em ambiente Proot

## Instalação
### Obs! Necessário ter no mínimo 2GB de espaço em disco.

#### Instale um ambiente proot ao termux:
```
apt install proot-distro -y && 
proot-distro install debian && proot-distro login debian
```

#### Instale o katoolin dentro do ambiente proot:
```
apt-get update && 
apt-get install python2 git -y && 
git clone https://github.com/LionSec/katoolin.git && 
cd katoolin && 
python2 ./katoolin.py
```
Adicione o repositório do Kali ao ambiente proot:

Ferramentas:

[-] Setoolkit
[-] Metasploit
[-] 
