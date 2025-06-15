# frepo
Script que usa o Whiptail para alterar a região dos repositórios no Fedora Linux.

# Instrições de instalação
Instale o whiptail
```
sudo dnf install whiptail
```
Clone o repositório
```
git clone https://github.com/Ferlinuxdebian/frepo.git
```
Instale a aplicação
```
cd frepo/ && chmod +x frepo && sudo cp frepo /usr/local/bin
```
Chame a aplicação como root 
```
sudo frepo
```
