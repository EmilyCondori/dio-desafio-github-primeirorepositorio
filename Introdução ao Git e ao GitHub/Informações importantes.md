Git e Github são utilizados no dia a dia das pessoas que criam software por um motivo bem simples: ter uma forma fácil de gerenciar o código fonte da aplicação, do sistema, do produto.

## O que é Git?

O Git é um sistema de controle de versão distribuído e amplamente adotado. O Git nasceu e foi tomando espaço dos outros sistemas de controle. Seu criador principal é o mesmo que o do Linux: Linus Torvalds, e ganhou o coração das pessoas que trabalham com open source.

## O que é GitHub?

O Github tem sim muita relação com o Git. GitHub é uma plataforma para gerenciar seu código e criar um ambiente de colaboração entre devs, utilizando o Git como sistema de controle. Ele vai facilitar o uso do Git, escondendo alguns detalhes mais complicados de setup. É lá que você provavelmente vai ter seu repositório e usar no dia a dia.

## Os conceitos do Git

Para começar a utilizar o GIT, é importante que você reconheça e compreenda alguns dos principais conceitos utilizados pela ferramenta. Algumas nomenclaturas básicas muito comuns na manipulação de códigos-fonte no GIT e no GitHub.

### Repositório

Os **repositórios** são os ambientes criados para armazenar seus códigos.

Você pode possuir um ou mais repositórios, públicos ou privados, locais ou remotos, e eles podem armazenar não somente os próprios códigos a serem modificados, mas também imagens, áudios, arquivos e outros elementos relacionados ao seu projeto.

É através dos seus repositórios públicos que outros programadores poderão ter acesso aos seus códigos no GitHub, podendo, inclusive, cloná-los para adicionar melhorias.

### Branch

**Branch** é o nome dado a uma versão (ramificação) do projeto. 

Isso é útil porque possibilita gerenciar múltiplas alterações acontecendo simultaneamente. Por exemplo, podemos fazer com que cada equipe de desenvolvimento

### Merge

Para unir as modificações feitas em um branch ao código original, utilizamos o comando **merge**.

Com esta funcionalidade, todas as alterações feitas em cópias manipuláveis são inseridas, após aprovadas, no código-fonte original sem complicações.

### Fork

Quando um profissional desenvolvedor precisa começar a trabalhar em um projeto, seu primeiro passo é copiar este repositório para a sua máquina.

Este processo é realizado pelo comando **fork**.

O fork também é uma funcionalidade útil quando um membro da equipe precisa pegar um código público para manuseá-lo em um editor de código local ou interno.

Principais comandos Git
-----------------------

Se você estiver familiarizado com alguns dos principais comandos do GIT, seus primeiros passos na ferramenta podem se tornar mais descomplicados.

Para isso, trouxemos abaixo uma lista dos comandos mais utilizados pelos programadores(as) e o que eles significam.

* **Init**: este comando dá origem a um repositório novo, local ou remoto, ou reinicializa um repositório já existente;

* **Clone**: este comando clona o código de um repositório para sua manipulação em outro ambiente;

* **Commit**: este comando move os arquivos da _state area_ para um repositório local;

* **Add**: este comando adiciona um arquivo alterado a uma _staging area_, ou seja, o prepara para ser vinculado a um _commit_;

* **Push**: este comando envia arquivos de um repositório local para um repositório remoto. No GitHub, por exemplo;

* **Pull**: ao contrário do push, este comando traz um arquivo do repositório remoto para o repositório local.

* **Merge**: este comando serve para unir arquivos alterados ao arquivo original de um projeto. Em outras palavras, é ele quem une os branchs as _commits_.

* **Log**: este comando permite a visualização do histórico de _commits_ de um arquivo ou usuário, ou o acesso de uma versão específica.
