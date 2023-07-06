# Treinamento Git
versionamento: registro de mudanças em arquivos, que possibilita recuperação
ou acesso a versões anteriores. Permite desenvolvimento de códigos em colaboração com outros

git: é um sistema de versionamento de códigos, que guarda os registros de versão como snapshots(foto), além da referência para essa foto

## Gravando Mudanças no Repositório
estados: untracked, unmodified, modified, staged

* git status: verifica o status dos arquivos
* git add: add arquivos para o estagio staged
* git diff: apresenta as modificacoes que foram realizadas em cada arquivo
* git commit: git commit add as modificacoes numa branch localmente
* git log: mostra as versoes e commits de cada usuario
* git restore: restaura até a modificação anterior a atual
* git push: add os arquivos a um repositorio remoto
* git pull: atualiza o repositorio local com o remote e já faz um merge
* git fetch: puxa as atualizaçoes do repositorio porem nao atualiza o local,
o ideal é utliza-lo com o git diff, para ver quais atualizacoes podem impactar ou nao no seu codigo

## Branchs
branchs: ramificações no código fonte
* git checkout: faz a troca para a branch desejada
* git branch: cria a branch desejada