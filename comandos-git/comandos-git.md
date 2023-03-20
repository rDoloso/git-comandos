# **Comandos GIT/GIT Hub**

## **Git config**
- git config --global user.name "name"
- git config --global user.email *email do usuario*

## **Git help**
- git help *comando*
- git *comando* --help

## **Criando Projeto**

- ## git init
> Cria um sbdiretório chamado _.git_ que contem todos os arquivos necessários de seu repositório

- ## git clone
>Você clona um repositório com git clone url. 
 
 ## **Comandos Básicos**

 - ## git add
 >Adiciona uma alteração no diretório ativo ; No entanto, git add não tem efeito real e significativo no repositório — as alterações não são gravadas mesmo até você executar git commit .

 - ## git status
 >exibe as condições do diretório de trabalho e da área de staging. Ele permite que você veja quais alterações foram despreparadas, quais não foram e quais arquivos não estão sendo monitorados pelo Git.

 - ## git diff
 >mostra as linhas exatas que foram adicionadas e removidas 

- ## git commit
### git commit -m "mensagem"
>uma mensagem de registro do usuário que descreve as mudanças.
### git commit -a 
>permite commitar os arquivos versionados mesmo não estando no Stage

### git commit -am
>Um comando de atalho de usuário experiente que combina as opções -a e -m. Essa combinação cria de imediato um commit de todas as alterações preparadas e gera uma mensagem de commit integrada.

- ## git rm
>usado para remover arquivos individuais ou uma coleção de arquivos. ' git rm *arquivo* '

- ## git mv
> Move ou renomeia arquivos; 
git mv *arquivo1* *arquivo2/diretorio*

- ## git branch 
>permite criar, listar, renomear e excluir ramificações.

## **Compartilhar e Atualizar Projetos**

- ## git pull
>Incorpora as alterações de um repositório remoto no branch atual.

- ## git push 
>é o comando em que você transfere commits a partir do seu repositório local para um repositório remoto; 