Olá mundo
----------


Antes de algo parar no histórico, precisamos dar dois passos:

1. Adicionar arquivos na área "Staging" : 
  - `git add [nome do(s) arquivos]`
  - Verfifica com `git status -s`
2. Comitar: `git commit -m "Uma mensagem descrevendo a mudança"`

Para verificar:

```
git log 
```
O histórico deve mostrar "Uma mensagem descrevendo a mudança", com nome do autor, data, e ID do commit (commit hash)

Para mandar as alterações para o github:

```
git push origin master # onde master é o nome do branch. Nem sempre vai ser este nome
```

```
git status -s # Mostra o status dos arquivos
git diff      # Mostra o diff dos arquivos que estão "fora da caixa"
git diff --cached # Mostra o diff dos arquivos que estão "dentro da caixa"
```
 
A "caixa" é a área "stage", ou seja, a área que tem arquivos prestes a ser comitados.

## Para sincronizar com o github

```
git push origin master # atualiza o github
git pull origin master # busca dados o github
```

## O que eu fiz

```
# adiciona uma "nuvem" - um repositório central, que é, neste caso, no github
git remote add origin git@github.com:mjacobus/git-augusto.git
```

## Clonando um projeto

```
git clone git@github.com:mjacobus/git-augusto.git
```
