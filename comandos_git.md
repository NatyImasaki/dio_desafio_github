# Git e Github

Terminal comandos 

- ls - lista os diretórios contidos na pasta em que estamos
- ls -a - lista diretórios ocultos
- cd / - permite que naveguemos nas pastas
- cd .. - permite que voltemos uma pasta
- clear - limpa o terminal
- rm -rf nome do diretório - para deletar um diretório
- openssl sha1 - trás determinado arquivo escolhido em um código criptografado
- mkdir nome da pasta - para criar um nova pasta

Git comandos

- git init - inicia um repositorio git
- git config - -global user.email "email”
- git config - -global user.name nome do usuário
- git add * - adiciona todos os arquivos modificados ao staged
- git add . - adiciona todos os arquivos dão repositório ao staged
- git add nome do arquivo - adiciona um arquivo específico ao staged
- mv nome do arquivo ./novo repositório/ - move o arquivo para outra pasta
- git restore - -staged nome do arquivo - para retornar o arquivo do staged

Comandos do Git para o GitHub

- git remote add origin + link do repositório criado no GitHub - para cadastrar um repositório remoto
- git remote -v - lista as listas de repositórios remotos cadastrados
- git push origin(que leva o link do nosso repositório) master - empurrar arquivos para o repositório remoto
- git pull origin(que leva o link do nosso repositório) master - puxar arquivos para o seu repositório na maquina
- git clone + link do repositório a ser clonado - para clonar repositório