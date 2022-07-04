 # Git
    * git init: Inicializando repositorio local
    * git status: Verificando quais arquivos estão com ou sem versionamento
    * git add --all: Adicionar todos os arquivos modificados para o repositorio local
    * git commit -m "" : Adicionar no repositorio local arquivos que foram mudados.
    * git diff: As diferenças que existe entre commits
    * git log: Mostrar todos os commits feitos ate hoje.
    * git checkout numero_commit: Retorna para esse ponto do versionamento;
    * git reset --hard: Desfazer todas as alteracoes feitas de todos os arquivos alteracoes nesse momento. 
    * git push: Adicionando as alteracoes feitas no servidor


    * git branch: Listar todas as branchs
    * git branch 'nome': criar uma branch
    * git checkout 'nome': Muda da branch atual para outra 
    * git checkout -b 'nome': cria uma branch e ja faz a mudança para a mesma
    * git push --delete origin nome
    * git branch -m "nome da branch" (Renomear localmente)

# Mesclar altercaoes
   Especificar qual branch voce que puxar alteracoes 
   Vamos supor voce esta na branch X e fez diversas alteracoes
   Entao precisa pegar essas alteracoes e colocar na branch principal chamar de Y
   Faça um push de tudo que voce fez para o servidor da branch X
   "git checkout Y" para ir direto para branch Y
   utilize o seguinte comando: git merge X
   Com isso tudo que esta em X ira para Y


# Hack
   * git commit -a -m "commit" -> mesma coisa de fazer um add . e um -m so que tudo junto

# tag

criar tag: git tag -a "nome da versao" -m "descricao"
enviar tag: git push origin "nome da tag"
git checkout "nome da tag"

# Stash 

   ADicionar em memoria o commit 
   git stash save "descricao do stash"
   git stash apply: pega o ultimo stash feito e adiciona 
   git stash pop : pega o  ultimo stash feito adicionando e deletando

# Fetch
   Tras alteracoes que vem do repositorio sem fazer modificaoes em local
   Tras: nopvas branchs, tags, novos commits que estao na maquina local.

# Rebase
   fsdfsdfsdf