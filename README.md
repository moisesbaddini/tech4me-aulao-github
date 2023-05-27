# tech4me-aulao-github

Repositório com comandos úteis e prática do Git e Github para os alunos do Tech4me 2023

## Criando sua conta

Acessar https://github.com

Selecionar opção Sign up - Para registrar

Crie sua conta usando um **Chat** com inteligência artificial

## Conceitos

### Repo

- Repositório = repository

https://github.com/new

- Nome do repositório deve ser único

convenção: colocar sempre em minúsculas, com hífen para separar palavras

Não aceita espaços no nome do repo

Capriche da descrição

### Create repository

## Branch

Estamos falando de árvore aqui

- Tronco - Trunk
- Ramos - Ramificação - Branches
- Folhas - Nós - Nodes

* Main - (Antigamente era chamado de master)
  > Main = Principal, ou seja, o tronco da árvore
  > Seu código fonte correto, o publicado, o pronto - que não está sujo com alterações de outras pessoas do time.

## Instalando um cliente Git no seu computador

https://dev.to/womakerscode/tutorial-instalando-configurando-e-inicializando-o-git-no-windows-57cj
Procure também pelo TortoiseGit
https://tortoisegit.org/

Clicar com o botão direito na pasta, selecionar:

> GIT bash here...

---

## Todos os comandos abaixo são LOCAIS (apenas no meu computador)

## Clonar um repositório

Clone = cópia local = o mesmo que está na internet está copiado no seu computador.

`git clone "endereço copiado do Github no botão: verde`
Confere lá no Github (site)!

Code

Aba HTTPS

### Visualizar as diferenças entre o anterior e as modificações que fiz agora:

`git status`

`clear` Limpar o terminal

`git add nome-do-arquivo` adiciona arquivos ao versionamento

o tempo todo pode ser dado esse comando

`tecla tab` para completar o nome do arquivo

Ao terminar, vamos **confirmar** nossas alterações:

(Fechar um pacotinho)

`git commit -m "Comentário"`
Sempre entre aspas duplas

Comentário: Explicar o fechamento do seu pacote, a confirmação do total do seu trabalho.

## Comando de sincronização do repo local com o repo remoto

`git push` Empurrar para o servidor

upload dos fontes

Vão aparecer telas iniciais de login no github

Confere lá no Github (site)!

Para ignorar arquivos no git, criamos um arquivo na main, sem nome de arquivo, com extensão `.gitignore`

`git add .` Adiciona todos os arquivos da pasta

`git diff nome-do-arquivo` Mostra as diferenças, tanto as adicionadas (staged) quando as ainda não add (unstaged)

`git restore nome-do-arquivo` Reverte o arquivo para as alterações do último add
