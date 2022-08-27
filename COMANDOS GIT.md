// PARA INICIALIZAR O GIT NO REPOSITORIO
git init

// PARA SUBIR TODOS OS ARQUIVOS
git add . 

// PARA SUBIR APENAS UM ARQUIVO
git add index.html

// PARA VISUALIZAR OS ARQUIVOS QUE IRÃO SUBIR PARA O GIT
git status

// APLICA UM COMENTÁRIO NO CODIGO.
git commit -m "Primeiro Commit"

//APONTAR PARA O GIT
git remote add origin https://github.com/HaelioMarcio/website.git

// CRIAR UMA NOVA RAMIFICAÇÃO BRANCH CHAMADA MAIN
git branch -M main

// SUBIR ARQUIVOS PARA O GIT
git push -u origin main


// CLONAR PROJETO
git clone https://github.com/HaelioMarcio/website.git

// BAIXAR AS ULTIMAS ALTERACOES
git pull
