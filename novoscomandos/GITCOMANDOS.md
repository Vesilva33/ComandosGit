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


commits objeto junta tudo aponta para arvore parente autor  mensagem timestamp carimbo de tempo.
 

commits e unico para cada autor commit aponta arvores e aponta blob se algo muda no commit muda toda as chaves.

comandos basicos do Git iniciar o git iniciar o versionamento
criar commit


•	git init
•	git add
•	git commit


veschimmels@verusca MINGW64 /c
$ ls
'$Recycle.Bin'/             ESD/                    ProgramData/
'$Windows.~WS'/             eSupport/               Recovery/
'$WinREAgent'/              hiberfil.sys            S400CA.BIN
'Arquivos de Programas'@    Intel/                  sources/
 Boot/                      MSOCache/               swapfile.sys
 bootmgr                    nlw/                   'System Volume Information'/
 BOOTNXT                    OneDriveTemp/           Users/
 DiscordSetup/              pagefile.sys            Windows/
'Documents and Settings'@   PerfLogs/               Workspace/
 DumpStack.log.tmp         'Program Files'/
 eclipse/                  'Program Files (x86)'/

veschimmels@verusca MINGW64 /c
$ cd W
Windows/   Workspace/

veschimmels@verusca MINGW64 /c
$ cd Workspace/

veschimmels@verusca MINGW64 /c/Workspace
$ mkdir curso-git

veschimmels@verusca MINGW64 /c/Workspace
$ cd curso-git

veschimmels@verusca MINGW64 /c/Workspace/curso-git
$ git init
Initialized empty Git repository in C:/Workspace/curso-git/.git/

veschimmels@verusca MINGW64 /c/Workspace/curso-git (master)
$ ls

veschimmels@verusca MINGW64 /c/Workspace/curso-git (master)
$ ls -a
./  ../  .git/

veschimmels@verusca MINGW64 /c/Workspace/curso-git (master)
$ cd .git

veschimmels@verusca MINGW64 /c/Workspace/curso-git/.git (GIT_DIR!)
$ ls
config  description  HEAD  hooks/  info/  objects/  refs/

veschimmels@verusca MINGW64 /c/Workspace/curso-git/.git (GIT_DIR!)
$ cd ..

veschimmels@verusca MINGW64 /c/Workspace/curso-git (master)
$ git add *

veschimmels@verusca MINGW64 /c/Workspace/curso-git (master)
$ git commit -m "commit inicial curso"
[master (root-commit) 2ab2b89] commit inicial curso
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 GITCOMANDOS.md





criar repositorio

criar arquivo Markdown


Git init

cria se um repositorio

ummodified arquivo nao modificado
modified arquivo modificado
staged arquivos que estão se preparando para outro
tipo agrupamento

Git add
 untracked git não sabe quando usou Git add foi para
staged


Git add transita entra area working directory  e staging
area local repository


git status vai dizer como esta o arquivo

mv manda pasta para detro de uma pasta mas git não conhece a 
pasta


git add nome arquivo
git add*
Git add.
mandando staged mando commit moveu todos osarquivos
repositorio local.
publicando no github


configuração do git verificar
<<$ git config --list>>

refazer as configurações de email
<<$ git config --globlal --unset user.email>>

refazer as configuração de nickname
<<$ git config --globlal --unset user.nickname>>

adicionar repossitorio
<<$ git remote add origin https://github.com/Vesilva33/ComandosGit.git>>

publicar no github
<<$ git push origin master>>



<<conflitos>>

































