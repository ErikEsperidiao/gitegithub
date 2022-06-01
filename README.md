# beacademy-devstart-gitegithub

# Git e GitHub

# beacademy-devstart-gitegithub
> Repositório usado para publicação de projetos do programa Dev Start Paylivre junto com a Be Academy. <br>
> Abaixo listarei os códigos, comandos e funções do **Git e Github** aprendidos e praticados no programa.

# Comandos vistos no módulo Git e Github

## _Configuração inicial:_

```
git config --global user.name <br>
git config --global user.email
```

> - Configurando o nome do usuário e email. <br>
> - A partir desse comando todas as alterações e atualizações no git irão aparecer o autor e peródo que foram realizadas.

## _Repositórios:_

```
git init
```

> - Após criar uma pasta, abrir o cmd ou o guit bash com botão direito mouse iniciaremos um repositório.

```
git status
```

> - Criando um arquivo **‘arquivo.txt’** na pasta verificaremos se houve algum commit.
> - Verifica se a branch que você se encontra possui commits (atualizações) a serem feitos e se há algum processo pendente dando dicas sobre o qual o próximo passo a ser realizado.
> - Resumindo ele faz um gerenciamento dos processos.

```
git add arquivo.txt
git add .
```

> - Após verificar que houve uma atualização no repositório adicionaremos o comando add para irem para o processo de commit.
> - Preparando (empacotando) o que irá ser comitado.
> - Pode ser adicionado todos os arquivos (**_git add ._**) ou individulamente (**_git add arquivo.txt_**).

```
git rm --cached arquivo.txt
```

> - Caso queira desfazer a ultima ação.
> - Voltar ao estágio anterior.

```
git commit -m "mensagem relacionada ao commit"
```

> - Agora chegou a hora de comitar após criar ou atualizar um arquivo no repositório.
> - A mensagem (-m) geralmente é algo que tenha alguma ligação e influência com o commit.

```
git stash
git stash pop
git stash list
git stash pop stash@{1}
```

> - Salva alterações sem commit.
> - Restaura alterações salvas.
> - Lista as stashs.
> - Aplica stash específica.

```
git log
```

> - Histórico dos seus comits mostrando um _hash, branch dos seus comits, local, data, autor._

## _Ramificação:_

```
git branch
```

> - Mostrar qual é a branch que você está no momento.
> - Branch é como se fosse uma fotografia do seu sistema no ponto em que ela foi criada.

```
git branch nome_da_branch
```

> - Criar uma nova branch.
> - Usar nome específico para a funcionalidade dela.
> - Evitar letras maiúsculas, caracteres especiais e caso necessário, separar com traço ou underline.

```
git checkout nome_da_branch
```

> - Navegar de um branch para outra.

```
git checkout -b nome_nova_branch
```

> - Criar uma nova branch e já acessa ela diretamente (checkout).

```
git branch -d nome_da_branch
```

> - Remover uma branch.
> - No sistema geralmente serão mantidas apenas as branchs principais, sendo eliminadas as que foram criadas apenas para um uso específico.

```
git merge nome_da_branch
```

> - Quando quero atualizar uma branch com as modificações da outra branch.
> - Primeiramente se direcionar para a branch a ser atualizada usando o git checkout.
> - Logo após realizar o merge fazendo a atualização do arquivo.

## _Criando repositório:_

```
git clone codigo_copiado
```

## _Clonando o repositório através da chave SSH no git bash:_

> - Após criar o repositório no _github_ clicamos em **CODE** e selecinando a opção SSH copiamos o código.
> - Abrindo o gitbash dentro da pasta onde vai ser salvo os arquivos do projeto digitamos **_gitclone_** mais o código copiado.

```
git remote -v
```

> - Visualizar os repositórios remotos.

```
git push
```

> - Empurrando as atualizações para o repositório remoto.



## Para que serve
GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. É como uma plataforma social colaborativa, onde programadores e empresas colocam seus projetos para o desenvolvimento do código...

Git é o sistema de controle de versão open source mais usado no mundo atualmente! Ele é usado para controlar o histórico de alterações de arquivos e principalmente de projetos de desenvolvimento de software. Ele permite mais flexibilidade no fluxo de trabalho, segurança e desempenho.

O Git é mais utilizado de forma individual e o GitHub mais usado coloborativamente.
## Autores

- [@erikmacedo](https://github.com/erikmacedo)


# Olá, eu sou Erik Macêdo 👋


## 🚀 Sobre mim
Sou um programador em desenvolvimento, saindo do forno.


## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/erik-esperidi%C3%A3o-286383234)


