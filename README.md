# Instalador-Setoolkit
Instalador Setoolkit completo com a versão mais recente + Metasploit em ambiente Proot

## Instalação
#### Obs! Necessário ter no mínimo 2GB de espaço em disco.

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
##### Adicione o repositório do Kali ao ambiente proot:
Escolha as opçôes: `1`, `1`, `2` e depois que finalizar der Ctr+C pra sair do Katoolin

![katoolin main](https://github.com/Olliv3r/Instalador-Setoolkit/blog/main/media/katoolin.jpg)

#### Instale o setoolkit dentro do ambiente proot:
*Vá passear ou tomar um café enquanto o processo de instalação finalize*
```
apt-get install set -y
```

Depois que terminar é so brincar.

Ferramentas:

- [x] Social-Engineer Toolkit
- [x] Metasploit-framework
- [x] Aircrack-ng
- [x] Nginx
- [x] Apache2
- [ ] Outros
