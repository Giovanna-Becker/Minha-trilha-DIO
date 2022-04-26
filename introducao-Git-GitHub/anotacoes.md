# Introdução ao Git e GitHub

Antes de entender o Git e GitHub é preciso aprender a usar o terminal do computador/notebook, ou o básico dele.

| Comandos | Funções |
| :---: | :---: |
| **dir** ou **ls** | Mostrar conteúdo de uma a pasta |
| **cd** / **cd ..** | Entrar em uma pasta / Sair de uma pasta |
| **mkdir** | Criar uma pasta |
| **cls**, **clear**, *ctrl + l* | Limpar tela |
| **echo** *nomedoarquivo .terminal* | Criar um arquivo |
| **del** / **rmdir** *pasta* **/S /Q**, **rm - rf** | Deletar arquivos / deletar pastas |
| **mv** *arquivo* ./ *pasta desejada* / | Mover arquivo de uma pasta para outra |

**Obs**: Esses comandos também podem servir para o Git Bash.

O Git possui um código de segurança para todos os seus projetos, chamados de repositórios. Cada um tem o seu código de 40 dígitos chamado de sha1 . 

Git e Git Hub são duas coisas distintas. O Git funciona como um tipo de terminal de computador/notebook, mas a diferença é que com ele se consegue criar repositórios com a sua conta, podendo também criar commits. Também se consegue conectá-lo com o seu Git Hub.

O Git Hub é um site ou app onde criando uma conta, o proprietário da conta pode enviar seus projetos de programação, seja eles individuais ou em grupo, para que possam ser visto por pessoas interessadas, incluindo empresas, caso o repósitório seja público.

Agora alguns comandos necessários para se usar o Git e e para mandar repositórios para o Git Hub.

| Comandos | Funções |
| :---: | :---: |
| **git init** | Incia um repositório no Git |
| **ls - a** | Mostrar pasta/arquivo oculto |
| **git status** | Informa se tem algum arquivo para comitar |
| **git add**, **git add** *nomedoarquivo*, **git add .** | Passar o arquivo ou todos os arquivos e pastas para stage, prontos para serem comitados. |
| **git commit -m " *mensagem* "** | Comita dos os arquivos e pastas |
| **git remote add** *nome linkdorepositório* | Salvar link do repositório no Git. *nome* é como o link vai ser chamado, geralmete é *origin*. |
| **git push** *nome* **master** | Enviar código do repositório local para o repositório remoto |
| **git pull** *nome* **master** | Para *puxar* o repositório remoto para o local |
| **git clone** *linkdorepositório* | Para baixar o repositório de outra pessoa |

Todo repositório precisa de um autor, para isso é necessário colocar seu nome e email no Git:

| Comando | Função |
| :---: | :---: |
| **git config --list** | Lista de configurações do seu Git |
| **git config --global user.email " *seu email* "** | Adicionar email |
| **git config --global user.name " *nome escolhido* "** | Adicionar nome do autor |
| Usar **--unset** antes de **--global** | Caso queira tirar o email e o nome  do seu Git |

Assim poderá fazer quandos projetos quiser e colocar todos no Git Hub para que outros possam ver e talvez até colaborarem com o projeto fazendo-o melhorar cada vez mais atraindo a atenção de empresas.