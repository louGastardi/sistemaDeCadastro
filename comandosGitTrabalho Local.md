Comandos importantes do GitHub para trabalhar localmente

Clonar repositório no desktop : 
prompt de comando > cd desktop > git clone link.git

visualisar alteracoes:
cmd > cd "nomeDaPasta" > git log

Visualisar alteracoes em uma linha: 
cmd > cd "nomeDaPasta" > git log --oneline

Para finalizar o comando:
depois do : > q

Verificar se teve atualizacoes no repositorio online:
"pasta do repositorio" > git pull "link do repositorio"

verificar alteracoes locais:
"pasta do repositorio" > git status

add commit para modificacoes:
"pasta do repositorio" > git commit index.html -m "Mensagem de commit"

modificações em mais de um arquivo, posso colocar só o ponto: 
"pasta do repositorio" >  git commit . -m "Mensagem de commit"

enviar arquivos para o repositorio online:
"pasta do repositorio" > git push origin main

Voltar para versao anterior:
"pasta do repositorio" > git restore --source CODIGO DA ATUALIZACAO .(para voltar a versao de todos os arquivos) / index.html  (para voltar a versao de um só arquivo)