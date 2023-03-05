# Comandos básicos do Git



Você encontrará informações sobre os seguintes tópicos:

- [Inicialização do repositório](https://github.com/RodrigoLMarques/dio-desafio-github/blob/main/Introdu%C3%A7%C3%A3o%20a%20GIT%20e%20GitHub/Comandos%20GIT.md#inicialização-do-repositório)
- [Configurações do Git](https://github.com/RodrigoLMarques/dio-desafio-github/edit/main/Introdu%C3%A7%C3%A3o%20a%20GIT%20e%20GitHub/Comandos%20GIT.md#configurações-do-git)
- [Operações com arquivos](https://github.com/RodrigoLMarques/dio-desafio-github/edit/main/Introdu%C3%A7%C3%A3o%20a%20GIT%20e%20GitHub/Comandos%20GIT.md#operações-com-arquivos)
- [Operações com commits](https://github.com/RodrigoLMarques/dio-desafio-github/edit/main/Introdu%C3%A7%C3%A3o%20a%20GIT%20e%20GitHub/Comandos%20GIT.md#operações-com-commits)
- [Visualização do histórico](https://github.com/RodrigoLMarques/dio-desafio-github/edit/main/Introdu%C3%A7%C3%A3o%20a%20GIT%20e%20GitHub/Comandos%20GIT.md#visualização-do-histórico)
- [Ramificações e tags](https://github.com/RodrigoLMarques/dio-desafio-github/edit/main/Introdu%C3%A7%C3%A3o%20a%20GIT%20e%20GitHub/Comandos%20GIT.md#ramificações-e-tags)
- [Operações com repositórios remotos](https://github.com/RodrigoLMarques/dio-desafio-github/edit/main/Introdu%C3%A7%C3%A3o%20a%20GIT%20e%20GitHub/Comandos%20GIT.md#operações-com-repositórios-remotos)



## Inicialização do repositório

### git init

Inicia um novo repositório Git em um diretório existente ou vazio.

### git clone [url]

Cria uma cópia local de um repositório remoto existente.



## Configurações do Git

### git config --global user.name "[seu nome]"

Define o nome de usuário que será associado às operações do Git.

### git config --global user.email "[seu email]"

Define o endereço de email que será associado às operações do Git.

### git config --global core.editor [editor]

Define o editor de texto padrão que será usado pelo Git.



## Operações com arquivos

### git add [arquivo]

Adiciona um arquivo específico para o staging area.

### git add .

Adiciona todos os arquivos modificados e não rastreados para o staging area.

### git rm [arquivo]

Remove um arquivo do diretório de trabalho e da staging area.

### git mv [arquivo] [novo nome]

Move ou renomeia um arquivo.



## Operações com commits

### git commit -m "[mensagem do commit]"

Grava o snapshot atual do staging area em um novo commit.

### git commit -a

Faz o commit de todos os arquivos modificados, removidos e renomeados, mas não adiciona novos arquivos.

### git reset [arquivo]

Remove um arquivo da staging area, mas preserva as mudanças.

### git reset

Remove todos os arquivos do staging area, mas preserva as mudanças.

### git reset --hard

Remove todos os arquivos do staging area e descarta todas as mudanças.



## Visualização do histórico

### git log

Mostra o histórico de commits.

### git log --follow [arquivo]

Mostra o histórico de commits para um arquivo específico, incluindo renomeações.

### git diff [commit] [commit]

Mostra as diferenças entre dois commits.

### git show [commit]

Mostra as mudanças introduzidas por um commit específico.



## Ramificações e tags

### git branch

Lista todas as ramificações locais.

### git branch [nome da ramificação]

Cria uma nova ramificação.

### git checkout [ramificação]

Muda para a ramificação especificada.

### git merge [ramificação]

Combina a ramificação especificada com a ramificação atual.

### git tag [nome da tag]

Cria uma nova tag para o commit atual.



## Operações com repositórios remotos

### git remote add [nome] [url]

Adiciona um novo repositório remoto com um nome especificado.

### git remote -v

Lista todos os repositórios remotos.

### git push [nome do repositório remoto] [ramificação]

Envia a ramificação especificada para o repositório remoto.

### git pull [nome do repositório remoto] [ramificação]

Atualiza o repositório local com as mudanças do repositório remoto.

### git fetch [nome do repositório remoto]

Busca todas as mudanças do repositório remoto, mas não mescla com a ramificação atual.
