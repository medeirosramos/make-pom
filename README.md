
# make-pom

Script para converter Web Java Project em Maven Project, forked from sjbotha/make-pom.

Erro find: para MacOS a sintaxe é diferente.

Execução testada no Ubuntu, instalações necessárias:
apt install unzip

Comandos:

> mkdir libs 
> cp -R myproject/lib/* libs  
> git clone https://github.com/medeirosramos/make-pom.git  
> chmod +x make-pom/make-pom.sh  
> make-pom/make-pom.sh libs  
> nano lib/pom.xml  

Para verificação manual, exemplo:

> unzip jsf-impl.jar  
> nano META-INF/MANIFEST.MF  

No final do arquivo é possível ver a versão:  
Bundle-Version: 1.2.15
Bundle-Description: Mojarra JSF Implementation (javax.faces/1.2MR2) 1.
2_15-b01-FCS
Bundle-Name: Mojarra JSF Implementation 1.2_15-b01-FCS
Bundle-ManifestVersion: 2
Implementation-Title: Mojarra
Bundle-SymbolicName: javax.faces.jsf-impl
Tool: Bnd-0.0.249
Extension-Name: com.sun.faces 
Implementation-Version: 1.2_15-b01-FCS  
Implementation-Vendor: Sun Microsystems, Inc.  
