git config --global user.name "jonas.arruda"
git config --global user.email jonasjohnny.sa@gmail.com
ssh-keygen -t rsa -b 4096 -C jonasjohnny.cg@gmail.com

ira retornar algo como:

Generating public/private rsa key pair.
Enter file in which to save the key (/home/ads/.ssh/id_rsa): ("deixe em branco pois vai criar o arquivo com o nome --> id_rsa)
Enter passphrase (empty for no passphrase): ("caso queira inserir uma senha para o arquivo")
Enter same passphrase again: ("repita a senha ou deixe em branco caso não tenha informado senha")
Your identification has been saved in /home/ads/.ssh/id_rsa
Your public key has been saved in /home/ads/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:0uHBDVF4tm0XogGmhChhqYZt8FPuaZ8wUCjndzfA3uM jonasjohnny.cg@gmail.com
The key's randomart image is:
+---[RSA 4096]----+
|.o.o o. ==.      |
|=.+ +.o+.o+ . .  |
|oO + ..o+o.= . . |
|o.B o oo=oo o .  |
|.. = o.oSo . .   |
|    *  .E        |
|   . + .         |
|      o          |
|                 |
+----[SHA256]-----+

Digite o comando: 
$ cat  /home/ads/.ssh/id_rsa.pub

ira mostrar a Chave do arquivo
ssh-rsa ***************conteudo*da*chave*************** seu-email@gmail.com

Esteja logado no seu github:
Digite https://github.com/settings/ssh/new

informe o campo com titulo e chave

Pronto estará autorizado a salvar seus projetos em seus repositorios do GiT.