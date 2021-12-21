# Estudo: Markdown
Este repositório tem o objetivo de descrever como funciona a *síntaxe* de formatação de arquivos do tipo **markdown**.

**Todo esse trecho está em negrito**

*Todo esse trecho está em itálico*

### O que é o GIT?

<img alt="Logomarca do Git" src="https://initialcommit.com/img/initialcommit/baby-git-release.png">

Git é um sistema de controle de versão distribuído gratuito e de código aberto projetado para lidar com tudo, desde projetos pequenos a muito grandes com velocidade e eficiência.

Git é fácil de aprender e ocupa uma área pequena com desempenho extremamente rápido . Ele supera as ferramentas SCM como Subversion, CVS, Perforce e ClearCase com recursos como ramificação local barata , áreas de teste convenientes e vários fluxos de trabalho .

O Git pode ser baixado clicando <a href="https://git-scm.com/downloads">AQUI</a>

### O que é o Github?

<img src="https://enotas.com.br/blog/wp-content/uploads/2021/02/GitHub.jpg">

O GitHub é considerado é uma ferramenta essencial para engenheiros de software, com uma popularidade sem igual. Atualmente, ele acomoda mais de 25 milhões de usuários. Isso significa que há um número considerável de profissionais que estão procurando o GitHub para melhorar o fluxo de trabalho e a colaboração.

Em suma, o GitHub é um serviço baseado em nuvem que hospeda um sistema de controle de versão (VCS) chamado Git. Ele permite que os desenvolvedores colaborem e façam mudanças em projetos compartilhados enquanto mantêm um registro detalhado do seu progresso.

### Processo de comunicação entre repositório local e remoto

<img src="https://i.stack.imgur.com/1wPcg.png">

* git init: Cria um repositório Git vazio ou reinicializa um existente
* git add: Adiciona o conteúdo do arquivo ao índice
* git status: Mostra o status da árvore de trabalho
* git commit: Grava alterações no repositório
* git branch: Listar, criar ou excluir branches
* git remote: Gerenciar conjunto de repositórios rastreados
* git push: Atualizar referências remotas junto com objetos associados

### Processo prático

1. Acessar o repositório local e executar o git bash (terminal git) dentro deste diretório
2. No git bash executar o comando git init
3. Executar o comando git add .
4. Executar o comando git commit -m "first commit"
5. Após a criação do repositório remoto no Github, executar o comando: git branch -M main
6. Executar o comando git remote add origin "url do repositório remoto"
7. Executar o comando git push -u origin main

**OBS.:** Para a realização dos procedimentos anteriores, é necessário a autenticação do usuário do Github no terminal do Git (user.name, user.email, token)
