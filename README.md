# linux xampp desktop shortcut launcher

this project consists of adding a shortcut to the xampp program in linux ubuntu and derivatives that use the **.desktop** program shortcuts


# Files

there are 2 types of files:
The **xampp.desktop** is the shortcut itself
there are also shell sript files to run the xampp services **start stop and restart** commands

## Installation
Move all files to the **.local/share/applications** folder located inside the user folder. Full path: /home/*%userprofile%*/.local/share/applications

## Attention!

 - It is necessary to **enter the user's password in the shell script files**, as the **commands run with sudo**
 - In the **xampp.desktop** file the item **Icon=** references the icon path
 - In the **xampp.desktop** file the **Exec=** items reference the path to the shell scripts



# 




# Atalho para o Xampp Linux

este projeto consiste em adicionar um atalho para o programa xampp no linux ubuntu e derivados que usam os atalhos do programa **. desktop**


# Arquivos

existem 2 tipos de arquivos:
O **xampp.desktop** é o próprio atalho.
Também existem arquivos shell scripts para executar os serviços com os comandos **start  / stop / restart** do xampp  

## Instalação
Mova todos os arquivos para a pasta **. Local/share/applications** localizada dentro da pasta do usuário. *Caminho completo: /home/%userprofile%/.local/share/applications*

## Atenção!

  - É necessário **inserir a senha do usuário nos arquivos shell scripts**, pois os **comandos são executados com sudo**
  - No arquivo **xampp.desktop**, o item **Icon=** faz referência ao caminho do ícone
  - No arquivo **xampp.desktop**, os itens **Exec=** fazem referência ao caminho para os scripts de shell 
