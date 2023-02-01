
# make-pom

Script para converter Web Java Project em Maven Project, forked from sjbotha/make-pom.

Erro find: para MacOS a sintaxe é diferente.

Execução testada no Ubuntu, instalações necessárias:
apt install unzip

Comandos:

> mkdir libs 
> cp -R myproject/lib/* libs  
> 
> git clone https://github.com/medeirosramos/make-pom.git  
> chmod +x make-pom/make-pom.sh  
> make-pom/make-pom.sh libs  
> nano lib/pom.xml  
