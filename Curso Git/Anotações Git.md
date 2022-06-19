# Anotações do curso de Git/Github

#### Essas anotações estão escritas de forma com que eu consiga entender e lembrar do conteúdo em que eu estudei, por isso pode parecer um pouco confuso para quem está lendo.



### Comandos no terminal
- dir - Lista as pastas do diretório 
- cd - muda o diretório ::: cs / - vai para o diretório do disco C 
- cd .. - volta para o diretório anterior 
- cls - limpa a tela 
- mkdir (nome) - cria pasta 
- echo (texto) > (nome.txt) - cria um txt com o texto digitado dentro 
- del (arquivo ou pasta) - deleta tudo que está dentro da pasta, mas a pasta fica 
- rmdir (pasta) /s /q - Deleta toda a pasta

### Atalhos terminal
- TAB - Auto completa a palavra 
- SETA PARA CIMA - Mostra os comandos digitados anteriormente



### Comandos git
- ls - lista as pastas
- ls -a - mostra arquivos ocultos
- git init - inicia o git dentro da pasta, e cria um repositorio no git 
- git config --global user.email ("email") - comando para adicionar email aos commits
- git config --global user.name (nome) - adicionar um nome aos commits
- git config --global --unset user.(email ou name) - para resetar as configs de email no commit
- git add * - pega tudo que foi modificado e add para staged
- git add (arquivo) (mais arquivos) - para colocar no staged as novas modificações para depois commitar
- git commit -m "texto do commit" - cria o commit de tudo que esta na pasta
- git status - mostra o status de todos os arquivos
- mv (arquivo) ./(pasta) - move um arquivo para dentro de uma pasta
- echo > (nome arquivo) - cria um arquivo, REDME.md por exemplo



- git remot -v 
- git remote add origin (link do repositorio) 
  (origin é o apelido do repo, então posso usar qualquer um, porém normalmente se usa o origin mesmo)
- git push origin master - da o push para o github
- git pull origin master - pega o conteudo do repositorio remoto para o seu repositorio local
- git clone (url repositorio) - baixar repositorios, ja vem com a pasta .git

### Atalhos 
- cntrl + l - limpa a tela