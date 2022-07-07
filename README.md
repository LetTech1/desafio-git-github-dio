# Resumo do curso de Git/Github - Dio 💻
A criação desse projeto tem o intuito de colocar em prática alguns ensinamentos sobre Git e Github, apresentados pelos cursos da plataforma Dio.

## Instalação
> Acesse o [site](https://git-scm.com/downloads) do Git e realize o download
> Após realizar o download, é necessário executar o arquivo, assim, fazendo a instalação

## Diferença entre Git e GitHub
De maneira simples, o Git é seu repositório local, isto é, com ele conseguimos gerar registros do nosso projeto mantendo o controle em quais arquivos foram alterados, quando foram alterados e por quem.
Assim, é possível manter uma linha do tempo de um projeto e voltar nesses registros quando for necessário. 

Já o GitHub é um repositório remoto, isso significa que ele é uma plataforma onde você pode armazenar seus projetos. É como se fosse uma rede social, só que de códigos, onde seus desenvolvedores podem disponibilizá-los para outras pessoas verem.

## Comandos básicos com Git/Github
Vamos imaginar que criamos um projeto em uma pasta especifica, sendo assim, devemos abrir o GitBash, que nada mais é do que o console pertencente ao Git, onde podemos realizar ações através de comandos. Podemos fazer isso de duas formas:
* É possível clicar na tecla Windows e pesquisar por "Git Bash", feito isso, será necessário navegar até a pasta onde está seu projeto
* Você também pode ir direto na pasta do projeto, clicar com o botão direito do mouse e selecionar "Git Bash Here", assim ele já vai abrir o console direto na pasta desejada.

Após realizar esse primeiro passo, iniciamos os comandos no Git:
* git init (ele inicia o repositório)
* git status (mostra os arquivos que não estão sendo controlados pelo git)
* git add . (adiciona todos os arquivos da pasta, caso você deseje adicionar um específico, ao invés de usar o . você deve colocar o nome do arquivo)
* git commit -m "coloque algo que identifique a alteração" (o commit basicamente junta tudo)

Agora vamos adicionar nosso projeto no GitHub:
No GitHub é necessário se identificar, para que ele saiba quem realizou alteração no código, sendo assim:
* git config --global user.email "leticiafelix@..."
* git config --global user.name "Letícia"
* git remote add origin git@github.com:... (aqui você insere o link disponibilizado pelo GitHub)
* git status (para verificar os arquivos)
* git add . (adicionar os arquivos)
* git commit -m "" (juntando todos arquivos)
* git push origin master (ele enviar todas as alterações feitas localmente no seu projeto, para seu repositório remoto, isto é, GitHub)

Caso você deseje clonar um projeto do github, isso é, baixar um projeto, podemos utilizar um comando:
* git clone git@github.com:... (aqui você insere o link do projeto que seja copiar)

## É isso pessoal, essas são algumas dicas que aprendemos no curso de git/github da dio. Caso você tenha interesse em realizar um curso para aprender mais sobre esse assunto, acesse o site da [DIO](https://www.dio.me/) e procure por [introdução ao Git e ao GitGub](https://web.dio.me/course/introducao-ao-git-e-ao-github/learning/75b9fe49-6ed4-4480-83a7-7e37fc356aa9)
