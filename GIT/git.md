# <font color=green>Git e GitHub</font>

## <font color=Purple>O que é Git?</font>
<p> É uma ferramenta de versionamento de arquivo, criada por Linus Torvalds. O Git serve para controle e acompanhamento de projetos de software.<br> Pode ser usado para projetos individuais ou em grupo.</p>

## <font color=grey>**Como usar o Git?**</font>
<p> Para iniciar o uso do Git é preciso instalá-lo em seu computador, conforme o link de download abaixo:</p>

[Clique aqui para o download](https://git-scm.com/downloads)

Selecione a opção de download de acordo com o seu sistema operacional e siga as etapas de orientação do site para completar a instalação.<br>
## <font color=grey>Configurando o Git</font>
Abra o prompt de comando no seu computador, em seguida digite **git --version** e aperte Enter<br>
Para configurar o computador inteiro digite **git config global "user.email you@example.com"** e aperte Enter<br>
Digite **git config global "user.name Your Name"** e aperte Enter<br>
Caso prefira configurar apenas um projeto, digite **git config local "user.email you@example.com"** e aperte Enter<br>
Digite **git config global "user.name Your Name"** e aperte Enter<br>
## <font color=grey>Iniciar um repositório</font>
- git init
- git status
## <font color=grey>Adicionar arquivos ao Stage</font>
- git add <file>
- git add .
## <font color=grey>Committ</font>
É a etapa que permite que você guarde o seu repositório da forma que ele está naquele exato momento, enviando para um sistema de controle de versão (ex.:GitHub).<br>
Para que isso aconteça basta usar o comando **git commit -m "comentário"**<br>
No comentário você pode sinalizar com poucas palavras o momento em que o seu repositório está, ou utilizar palavras chave, como por exemplo:<br>
- Teste;
- Criação botão "clique aqui";
- Atualização.<br>

Existe também o comando **git commit -am "comentário"**, onde é possível adicionar a alteração ao Stage e commitar no mesmo comando.<br>
## <font color=grey>Quando devo commitar?</font>
- Sempre que houver pequenas funcionalidades concluídas!<br>
- Nunca commite algo que não está funcionando.
## <font color=grey>Ignorar Arquivos</font>
O arquivo .gitignore é um arquivo de texto que diz ao Git quais arquivos ou pastas ele deve ignorar em um projeto.<br>
- git add .gitignore
- git commit m “Adicionando gitignore
## <font color=grey>Repositório Remoto</font>
Para enviar as alterações do projeto para o repositório remoto (utilizaremos o *GitHub*) é muito simples, basta utilizar o comando **<font color=yellow>git push**</font>.<br>
Este comando envia o código da Branch atual para a Branch correspondente no Repositório Remoto apontado pela Origin.<br>
<p><font color=yellow>Observação:</font> Não é possível fazer um git push se os repositórios não estão sincronizados. É necessário fazer um git pull primeiro , resolvendo eventuais conflitos.</p>

## <font color=grey>Clonando um Repositório</font>
Para clonar um repositório remoto você pode utilizar os comandos abaixo:<br>
- git clone + url do repositório remoto
- git clone + url do repositório remoto "nome_Novo_Diretório"

## <font color=grey>Atualizando Repositório Local (pull)</font>
Para atualizar um repositório local você pode utilizar os comandos abaixo:<br>
- git pull
- git pull pull <REMOTE_NAME>
- git pull pull <REMOTE_NAME> <BRANCH_NAME_LOCAL>
- git pull pull <REMOTE_NAME> <BRANCH_NAME_LOCAL> : <BRANCH_NAME_REMOTE>


## <font color=purple>O que é GitHub?</font>
É uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o _Git_.<br>
Essa plataforma tem várias vantagens, como:
- Poder trabalhar em equipe;
- Dividir partes do projeto;
- Segurança: não perder as versões que já foram hospedadas;
- Histórico e Ramificações;
- Organização: maior controle no acompanhamento dos projetos.
<p>Geralmente o código é aberto, o que permite realizar projetos compartilhados e manter o acompanhamento detalhado de seu progresso. A plataforma GitHub também funciona como rede social, conectando os desenvolvedores com os usuários.</p>

Você pode acessar o site do [GitHub](https://github.com/) e criar a sua conta clicando em Sign Up. Após criar sua conta você pode completar as informações de perfil e começar a criar repositórios para os seus projetos. 
