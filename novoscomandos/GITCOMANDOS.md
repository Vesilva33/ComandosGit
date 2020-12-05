#comandos curso git :)#




	
*Comandos inicias do Git*
•	Interface gráfica – são os sistemas operacionais.
•	CLI- linha de comando
O que vamos estudar?
1.	Mudar de pasta
2.	Listar pasta
3.	Criar pasta /Arquivos.
4.	Deletar pastas/Arquivos
WINDOWS X LINUX (UNIX)
-Cd                     -Cd
-Dir                    -ls
-MKDIR                 -MKDIR
- DEL/RMDIR            –RM-RF		           


1.	DIR
Diretório
2.	Ls
Diretório
3.	Cd
Base do diretório c:/ou diretório Linux
4.	Cd/Windows
Todas as pastas Windows dentro do c
5.	Retroceder no terminal de comando
cd..
6.	Limpar tela 
Cls –Windows
Clear-Linux
CTRL +L-Linux
 Cd w+tab –alto completa a pasta dentro cmd 

7.	Mkdir
Cria pasta .

 












Comandos 
Cd etc ls- acessar todos programas executados dentro  do Linux na pasta  interna.

Echo- print frase no terminal

Del- so deleta arquivo.

Instalar no Linux 
-cola código e da Enter 
•	git –status
•	git- - version
Mac os
INSTALAR HOMEBREW

Como funciona o Git
•	SHA1
•	OBJETOS FUNDAMENTAIS
•	SISTEMA DISTRIBUIDOS
•	SEGURANÇA

A encriptação gera conjunto de caracteres identificador de 40 dígitos.





O que são?

•	Blobs
•	Trees
•	commits


são os três tipos  básico responsáveis versionamento de código


blobs echo 'conteudo' | git hash -object --stdin
 
echo -e'conteudo'|openssl sha1

blob bolhas

blob
\0
olá mundo


 
tree
armezena blob monta estrutura de todos arquivos aponta blob ou outras tree(arvores) as arvores sha1 metadados das arvores


tree
\0
blob sa4d8s texto.txt


commits objeto junta tudo aponta para arvore parente autor  mensagem timestamp carimbo de tempo.
 

commits e unico para cada autor commit aponta arvores e aponta blob se algo muda no commit muda toda as chaves.

































