#### 20/07/2023

Curso Git e Github: estratégias de ramificação, Conflitos e Pull Requests


@01-GitHub e OpenSource

@@01
Introdução

Olá, pessoal, boas vindas à Alura, meu nome é Vinicius Dias e os guiarei nessa continuação do curso sobre Git e GitHub, em que teremos uma visão geral sobre o que é open source e como contribuir para projetos do tipo, especificamente trabalhando com o GitHub.
Veremos o que é uma issue, como abrir e fechá-la, como lidar com ela, de forma geral, o que pode ser um problema, um relatório de bug. Também entenderemos como gerenciar e lidar com pull request, ou seja, como enviar pedidos e sugestões de melhorias em código para projetos open source.

Aprenderemos boas práticas para contribuir, como não utilizar tantos commits e conseguir unir vários deles em um só. Falaremos sobre um controle um pouco mais refinado e avançado de versionamento, gestão de conflitos, busca avançada de commits, formas de encontrar modificações, entre outros.

Para continuarmos nessa parte de profissionalismo e boas práticas, falaremos sobre estratégias de branching, entendendo como organizar nossas branches de forma bem interessante. Depois, conheceremos ferramentas como o GitKraken, que nos auxiliará a executar estas alterações e boas práticas de Git e gerenciar o versionamento do nosso código de forma facilitada.

Além disso, conheceremos os eventos, os git hooks, ações que são executadas em determinados eventos. Assim, com apenas um push, seremos capazes de executar o deploy de uma aplicação, disponível para acesso. Será um curso bem interessante, relativamente curto, espero que vocês tirem bastante proveito.

Caso surja alguma dúvida no decorrer do curso, não hesite em abrir uma dúvida no fórum, e espero vocês no próximo vídeo para começarmos a colocar a mão na massa!

https://www.gitkraken.com/

https://cursos.alura.com.br/forum/curso-git-github-branching-conflitos-pull-requests/todos/0

@@02
Issues

Está na hora de conversarmos um pouco mais sobre o GitHub, o gerenciador de repositórios remotos, muito utilizado pela comunidade de desenvolvimento open source, ou seja, em projetos de código aberto. Isso quer dizer que o código será disponibilizado em algum lugar público, como o GitHub, para que outras pessoas possam contribuir sugerindo melhorias, implementando-as, solicitar features específicas, e assim por diante, tornando o projeto efetivamente colaborativo.
Você pode estar se perguntando: "vou desenvolver meu projeto e colocá-lo na internet para que todo mundo veja o meu código e copie meu trabalho?" Não é com esta mentalidade que o software livre funciona; quando desenvolvemos projetos de código aberto, pensamos nas vantagens e possibilidades que eles podem alcançar.

Alguns exemplos de projetos com códigos simples e abertos são o VS Code, editor que temos utilizado, o npm, gerenciador de pacotes usado para baixar dependências no JavaScript, e até linguagens como o PHP. Eles trazem muitas vantagens, dentre as quais permitir a melhoria contínua do código de maneira colaborativa. Para mais detalhes, fica a recomendação de se pesquisar um pouco mais a fundo sobre o assunto; existem inclusive cursos sobre Linux que tocam em open source, palestras na internet, como a da Daiane Alves no evento Darkmira Tour PHP em 2019, que fala sobre como empreender utilizando software livre, é bastante interessante pesquisar sobre tudo isso.

Voltando ao GitHub, que é a "casa" de muitos projetos open source, temos algumas boas funcionalidades, como as "Issues", ou "problemas", em tradução livre, em que é possível controlar as sugestões de melhorias, pedidos de novas funcionalidades, e assim por diante. Existem alguns projetos que utilizam as issues de forma até mais interessante, e como exemplo, está o repositório de uma comunidade chamada PHPRio, disponibilizado para cadastro de palestras ou palestrantes, o que é realizado por meio das issues do GitHub.

Assim, podemos filtrar palestrantes através da lista de issues do projeto! Conseguimos gerenciar este tipo de conteúdo, que não é um "problema" propriamente dito. Voltando para o nosso caso, poderemos começar a pensar na colaboração de outras pessoas. Para tal, criaremos uma sugestão, dentro de "Issues", clicando no botão "New issue", algo possível de se fazer em qualquer repositório.

O título poderá ser algo do tipo "Adicionar título na página", e a descrição, "A página contém apenas a lista dos cursos. Senti falta de um título.". Não é algo tão importante de início, mas vale ressaltar que é possível utilizar código markdown. Clicaremos no botão "Submit new issue" para enviar a issue, que passará a figurar em uma lista, a partir da qual, se você gerencia um projeto de software livre, conseguirá organizá-la por ordem de prioridade.

Sugiro que deem uma olhada nos projetos que vocês utilizam para verificar se são de código aberto, e se forem, verifiquem suas listas de issues, talvez haja algo com que vocês possam contribuir. Durante este curso entenderemos um pouco melhor sobre como fazer isto, também. Vamos resolver o problema que acabamos de criar a seguir.

http://github.com/phprio/cfp

@@03
Para saber mais: Open Source

Conversamos bem rapidinho sobre o que é um projeto Open Source, algumas de suas vantagens e como o GitHub pode nos ajudar na organização deste tipo de projeto.
Existem diversos projetos bem sucedidos que são Open Source, inclusive plataformas e linguagens de programação, como PHP, .NET Core, etc.

Material sobre Open Source na web não falta, mas só para dar uma referência, este é o link de uma palestra sobre projetos Open Source bem sucedidos, que a Daiane Alves apresentou no Darkmira Tour PHP 2019. Vale a pena conferir e estudar mais sobre o assunto.

http://slides.com/daianealvesrj/software-livre-para-empreendedores

@@04
Reportando... problemas?

Vimos no último vídeo uma funcionalidade interessante do GitHub: as issues. Com esta funcionalidade, podemos atingir alguns resultados interessantes na organização de um projeto.
Sobre o que podemos fazer com issues, avalie as afirmativas abaixo:

1) Podemos reportar problemas

2) Podemos sugerir melhorias no código

3) Podemos organizar quaisquer coisas que façam sentido para o projeto

As afirmativas 1, 2 e 3 estão corretas
 
Alternativa correta! Todas as afirmativas estão corretas, já que o propósito inicial das issues, como o nome já diz, era reportar e controlar os problemas e bugs de um projeto (afirmativa 1). Além disso, com o tempo, passaram a perceber que havia mais possibilidades nas issues, e elas foram utilizadas para sugestão de melhorias no projeto e pedidos de novas funcionalidades (afirmativa 2). Por fim, ótimos exemplos de usos das issues no GitHub são das comunidades PHPSP e PHPRio, que as utilizam para organizar os palestrantes e sugestões de palestras (afirmativa 3).
Alternativa correta
Somente a afirmativa 2 está correta
 
Alternativa correta
Somente as afirmativas 1 e 3 estão corretas
 
Alternativa correta
Somente a afirmativa 3 está correta
 
Alternativa correta
Somente as afirmativas 2 e 3 estão corretas
 
Alternativa correta
Somente a afirmativa 1 está correta
 
Alternativa correta
Somente as afirmativas 1 e 2 estão corretas
 
Alternativa errada! As afirmativas 1 e 2 estão corretas, já que o propósito inicial das issues, como o nome já diz, era reportar e controlar os problemas e bugs de um projeto (afirmativa 1). Além disso, com o tempo, passaram a perceber que havia mais possibilidades nas issues, e elas foram utilizadas para sugestão de melhorias no projeto e pedidos de novas funcionalidades (afirmativa 2). Mas não são somente estas afirmativas que estão corretas, a afirmativa 3 também está!

@@05
Pull Requests

Sobre as issues, ou problemas do GitHub, um ponto interessante é que se tivermos as permissões necessárias, ou seja, se formos os donos do repositório, ou fizermos parte da organização da empresa, poderemos fechar a issue ("Close issue"), indicando que o problema já foi resolvido. Se a issue estiver fechada, nestas condições, poderemos reabri-la para informar que o problema voltou a acontecer, por exemplo, e todo o histórico fica salvo no GitHub.
Vamos supor que outra pessoa da mesma equipe, Ana, já conhece o projeto e sabe como resolver o problema que publicamos anteriormente. Ela não poderá simplesmente editar o código criado pelo Vinicius. Isso evita que uma pessoa mal intencionada tenha acesso total ao código, criando bugs propositais, ou incluindo um código que não faz sentido. Então, mesmo que o projeto seja open source, existe sempre alguém validando estas alterações, garantindo que elas sejam de fato benéficas para o projeto.

Assim, o primeiro passo para que a Ana possa contribuir no projeto do Vinicius é criar uma cópia do mesmo para trabalhar nele e, no final, quando finalizada a solução da issue, ela enviará ao repositório do Vinicius apenas as alterações feitas. Vamos criar este repositório cópia!

Quando trabalhamos com controle de versões, principalmente com o Git e o GitHub, o nome deste repositório cópia é fork, que remete aos dentes de um "garfo", em inglês. Então, logados como Ana, clicaremos no botão "Fork" no topo direito da página. Ao atualizarmos a página, verificaremos a existência da cópia do projeto para analura, que é da Ana, e ela poderá editar este projeto da forma como preferir.

Temos todo este código na máquina local, no diretório "projeto", e garantiremos isto acessando o repositório pelo Terminal digitando cd ana/ seguido de cd projeto/. Executaremos git pull origin master, e teremos a mensagem de que este repositório não existe. Aqui, entra outro assunto: adicionaremos, com o origin, o repositório da Ana, o outro repositório, aquele que copiamos. Para isto, voltaremos ao GitHub e clicaremos em "Clone or download", um botão dropdown que exibe um link, que copiaremos.

No Terminal, digitaremos git remote add origin colar o link no comando e dar "Enter". E então traremos as alterações com git pull origin master. No VS Code, confirmaremos que o código está atualizado como esperávamos. Já temos o repositório local, como Ana, sincronizado com o nosso fork, no GitHub da Ana.

Feito isso, no código no VS Code, adicionaremos um título, acrescentando uma linha antes da abertura da tag <ul>: <h1>Cursos de DevOps</h1>. Criaremos um commit no Terminal começando por git status e git diff para verificarmos as modificações realizadas, e então git add index.html e git commit -m "Título adicionado". Repetiremos o mesmo processo após pularmos uma linha entre a linha recém implementada e <ul>, sendo portanto o último comando digitado git commit -m "Quebra de linha".

Feitas todas estas alterações, enviaremos os dados ao repositório com git push origin master. Porém, o envio será rejeitado, pois não temos permissão para isso. Para resolvermos isto, o primeiro passo será configurar o e-mail da Ana, com git config --local user.email "anaalura123321@gmail.com". Depois, usaremos git push origin master para verificarmos se, com isto, temos sucesso.

Não conseguiremos acesso, e o que acontece é que se fosse em um ambiente MacOX ou Linux, provavelmente você já teria recebido uma mensagem pedindo o login e senha do GitHub. No Windows, como já adicionamos um repositório do GitHub anteriormente, ele trabalha de forma diferente. A partir do momento em que adicionamos um repositório do GitHub, sempre que tentarmos enviar algo para lá, ele tentará utilizar estas credenciais.

Esta é a forma mais simples: apagaremos as credenciais do GitHub acessando "Painel de Controle > Contas de Usuário > Gerenciador de Credenciais > Credenciais do Windows". Dentre as Credenciais Genéricas, clicaremos na seta ao lado de git:https://github.com para que a informação seja expandida, e em "Remover". Assim, se tentarmos refazer o push, o GitHub nos solicitará os dados para login.

Faremos login como "analura", e agora, sim, conseguiremos enviar as alterações. Vamos atualizar a página com o projeto no GitHub, em que teremos mais commits adicionados — referentes ao título, e quebra de linha. De que forma enviaremos as modificações para o dono do repositório, ou seja, para o repositório do Vinicius?

Estas modificações são realizadas por meio de pull requests, um pedido de envio de modificação. Então, clicaremos no botão "New pull request", e o GitHub fará o trabalho de verificar se com o Git conseguimos fazer merges sem nenhum conflito, exibindo uma mensagem que diz que ambos os repositórios podem ser unificados sem nenhum problema, e mais abaixo, os commits enviados.

No fim, todas as alterações serão realizadas, neste caso, somente adicionamos duas linhas. Poderemos clicar em "Create pull request" para confirmar que queremos fazer esta ação, cujo título será "Adicionando título na página", sendo possível acrescentarmos um comentário, algo como "Adicionando um título para a página que antes não tinha.". Pressionaremos "Create pull resquest", e isto estará presente no repositório do Vinicius.

Poderemos confirmar isso logando como ele e acessando a aba "Pull requests" no GitHub. Analisaremos os commits e clicaremos em "Merge pull request" e "Confirm merge", já que não há nada a ser alterado. Com isto, teremos um pull request no status merged. É possível verificarmos o código, que estará com as alterações devidamente implementadas, e então fecharmos a issue, junto a um texto "Fechado pelo PR #2", clicando em "Close and comment".

A nossa issue estará fechada, e contendo um link para o último pull request junto a todas as alterações realizadas. Resumindo o que vimos, o Vinicius cria um repositório, a Ana enviou uma atualização, posteriormente revisado e autorizado pelo Vinicius, que enviou uma notificação informando que o pull request foi aceito.

Algo que não ficou tão legal, porém, é a lista de commits, pois o commit de quebra de linha não é relevante. Será que não seria interessante termos um único commit? Mas a Ana fez dois commits, e ela tem o direito de trabalhar com quantos quiser! Será que depois de realizar os commits, ela não conseguiria juntar vários em um só? Como será que conseguimos unir commits para ajudar quem for revisar o código?

@@06
Colaborando com outros projetos

Já vimos como sugerir melhorias ou reportar problemas utilizando issues, mas o nosso trabalho no mundo Open Source pode ser mais ativo. Através de pull requests, nós podemos enviar melhorias e correções para projetos.
Por que utilizar pull requests e não editar o projeto original?

Para utilizar uma buzzword (pull request) legal
 
Alternativa correta
Para tirar o maior proveito da ferramenta (GitHub)
 
Alternativa correta
Para garantir a qualidade do projeto pelos seus líderes e organizadores
 
Alternativa correta! Através de pull requests, os principais mantenedores de um projeto podem analisar todas as alterações, aprová-las ou reprová-las, dar feedback e interagir de uma forma geral. Pull requests não são utilizados apenas para projetos Open Source. Muitas equipes utilizam pull requests em seu dia-a-dia, para enviar as alterações de código para revisão de algum supervisor.

07
Unindo commits

Comentamos anteriormente que muitos commits para uma única alteração não é muito viável para quem está revisando o código, então vamos considerar outro problema para depois chegarmos a uma solução de unificação de commits. Começaremos criando, como Ana ("analura"), uma nova issue no repositório do Vinicius. O título será "Trocar ul por dl", e o comentário, "A lista de conteúdo pode ser melhor representada pela tag HTML <dl>".
A Ana, que quer contribuir neste projeto, já possui o fork do mesmo, em que irá trabalhar. No VS Code, então, substituiremos as duas ul por duas dl. No Terminal, executaremos git status seguido de git diff para verificarmos quais modificações foram realizadas, e então adicionaremos o arquivo, com git add index.html. Feito isto, digitaremos git commit -m "Trocando UL por DL".

Entretanto, além disto, queremos separar o título dos cursos de suas respectivas descrições, algo possibilitado por <dl>. Teremos o seguinte código HTML:

<dl>
    <dt>Vagrant</dt>
    <dd>Gerenciando máquinas virtuais</dd>
    <dt>Docker</dt>
    <dd>Criando containers sem dor de cabeça</dd>
    <dt>Ansible</dt>
    <dd>Sua infraestrutura como código</dd>
    <dt>Integração Contínua</dt>
    <dd>Maturidade e Produtividade no Desenvolvimento de Software</dd>
    <dt>Kubernetes</dt>
    <dd>Introdução à orquestração de containers</dd>
</dl>COPIAR CÓDIGO
Adicionaremos este commit com git add index.html, git commit -m "Separando os títulos" e, por fim, incluiremos quebras de linha no código:

<dl>
    <dt>Vagrant</dt>
    <dd>Gerenciando máquinas virtuais</dd>

    <dt>Docker</dt>
    <dd>Criando containers sem dor de cabeça</dd>

    <dt>Ansible</dt>
    <dd>Sua infraestrutura como código</dd>

    <dt>Integração Contínua</dt>
    <dd>Maturidade e Produtividade no Desenvolvimento de Software</dd>

    <dt>Kubernetes</dt>
    <dd>Introdução à orquestração de containers</dd>
</dl>COPIAR CÓDIGO
E criaremos mais um commit para isto, git add index.html, git commit -m "Quebras de linha", e assim teremos todas as alterações necessárias para criarmos o novo PR (pull request). Porém, antes disso, vamos conversar novamente sobre a quantidade de commits. Se executarmos git log --oneline, verificaremos que existem 3 commits a serem enviados, e então analisados pelo Vinicius. Poderemos juntá-los, e para modificarmos a linha do tempo do branch de forma interativa, isto é, selecionando os commits a serem unificados, utilizaremos git rebase -i HEAD~3.

Outra opção seria selecionar, copiar e colar manualmente o commit imediatamente anterior ao primeiro com o qual queremos trabalhar, acrescentando-o ao fim do comando git rebase -i.
Ao executarmos, receberemos a lista dos commits que queremos analisar. O primeiro comando, que por enquanto estará como pick, será responsável por definir se iremos juntar os commits ou não. Basicamente, teremos do commit mais antigo para o mais novo, de cima para baixo, e informaremos que queremos unificar "Quebras de linha" com o commit anterior, "Separando os títulos", e também com "Trocando UL por DL".

Para fazermos isto, substituiremos os pick por s, de squash, juntar, apertando:

pick 971dba0 Trocando UL por DL
s 3db095f Separando os títulos
s af37cf6 Quebras de linhaCOPIAR CÓDIGO
Com isso, os três commits se tornarão um só, o único que possui pick. Salvaremos, no caso de você estar utilizando o VIM, o atalho é ": + x", e será informado que precisaremos atribuir uma nova mensagem ao commit, que então será "Trocando UL por DL e separando os títulos", pois, para quem for revisar o código, as quebras de linhas não são tão relevantes.

Usaremos ": + x" para sair, e assim o Git já reescreve o histórico de commits. Executaremos git log --oneline e veremos apenas um commit, no lugar dos 3 anteriores. Vamos executar, então, git push origin master e verificar se o commit realmente chegou ao GitHub, no repositório da Ana. Se temos um commit novo e queremos enviá-lo para outro repositório, no caso, o do Vinicius, criaremos um novo pull request, clicando em "New pull request".

O título será a mesma mensagem do commit, e desta vez não acrescentaremos nenhum comentário. O Git indicará que não há nenhum conflito, então, logados como Vinicius, verificaremos o novo PR e, estando adequado, poderemos realizar o merge. Em seguida, iremos à lista de issues, que fecharemos, junto ao comentário "Resolvido pelo PR #4".

Notem que ao digitarmos "#", o GitHub nos ajuda mostrando todos os PRs recebidos, após o qual basta selecionarmos um.
Já entendemos o que são issues, pull requests, e como criá-los, o que é um fork, como unir commits — mas será que tudo isso só é possível de ser feito no GitHub? Será que ele é a única solução quando queremos trabalhar com código aberto, open source? Conversaremos sobre isto e conhecer algumas alternativas a seguir.

@@08
Pull request com um commit

Tendo entendido o que são issues e pull requests, nada mais justo do que enviar um pull request para resolver uma issue, certo? Mas quando desenvolvemos, podemos realizar vários commits, o que pode não ser tão interessante para quem for revisar o pull request.
Por que é interessante unir os commits em um único para enviar um pull request?

Para demonstrar domínio da ferramenta (Git)
 
Alternativa correta
Para diminuir o log
 
Alternativa correta
Para que o responsável pela revisão do projeto tenha um único commit a revisar, com todas as alterações necessárias
 
Alternativa correta! Revisar um único commit é bem mais fácil e rápido do que analisar diversos commits que resolvem um problema em comum. Por isso, nestes casos, é interessante utilizar o git rebase -i.

@@09
Para saber mais: Fechando issues

No último vídeo, nós vimos como enviar um pull request que resolve uma issue.
Se somos o organizador de um projeto, podemos agilizar o processo de fechar uma issue, informando diretamente no comentário do pull request.

Para que fique bem claro, vou deixar este link que explica em detalhes: https://help.github.com/en/articles/closing-issues-using-keywords.

https://help.github.com/en/articles/closing-issues-using-keywords

@@10
Alternativas ao GitHub

Falamos bastante sobre o GitHub anteriormente, já entendemos como criar issues e pull requests, unir nossos commits para facilitar o review das pull requests, mas será que só conseguimos fazer tudo isso usando o GitHub?
Existem várias outras soluções e alternativas; o GitHub é o mais conhecido e utilizado, inclusive todos os meus repositórios de códigos estão lá, mas existem soluções que podem trazer vantagens, como o Bitbucket conseguimos criar repositórios exatamente como no GitHub, organizando pull requests e issues da mesma forma.

Porém, no plano gratuito, o GitHub só permite acesso a repositórios públicos. Se temos um repositório a ser organizado e gerenciado por uma pequena equipe, ou mesmo uma única pessoa, e não queremos que ele fique público, será necessário pagar para utilizar o GitHub. Já no Bitbucket é possível marcarmos, na criação do repositório, se ele será público ou privado. Esta é uma das principais vantagens deste serviço, e sua interface, embora diferente da do GitHub, também é muito amigável, e ele é fácil de ser utilizado. Sugiro, como exercício opcional, que você crie o mesmo repositório criado no GitHub no Bitbucket, para verificar as diferenças e conhecer melhor.

Existem também ferramentas mais robustas, com mais funcionalidades para equipes maiores, em que o código não será necessariamente compartilhado publicamente. O GitLab é uma ferramenta muito interessante que permite o gerenciamento de ferramentas e servidores de integração e entrega contínua. Basicamente, é possível definir tarefas a serem executadas de forma muito fácil, em decorrência de alterações, pushes, no momento de rodar testes, verificar se o código está funcionando sem bugs, se o padrão de codificação está adequado, gerar relatórios com métricas, e por aí vai.

No fundo, tais opções fornecem vantagens a mais, porém, se você só está gerenciando repositórios Git, todos eles serão capazes de atingir o mesmo objetivo. As facilidades extras é que diferenciarão uma da outra, portanto convido vocês a criarem uma conta pelo menos no Bitbucket para testarem. E se vocês tiverem alguma sugestão de ferramenta similar, apresentem no fórum do curso.

Será que já vimos tudo sobre Git? Se quisermos trazer ao nosso commit um outro específico de outro branch, ou encontrar quem fez determinada alteração para tirar uma dúvida, consultar o histórico de commits, será que já conhecemos estas funcionalidades mais avançadas do Git?

Claro que não. Devemos sempre voltar um passo para trás para conseguir dar vários para a frente e aprender mais ainda. Então vamos deixar a parte de open source um pouco para lá e voltar para o Git para obtermos um controle um pouco mais avançado de versões, gestão de conflitos, e assim por diante.

https://bitbucket.org/

https://about.gitlab.com/

@@11
Para saber mais: Privados

O GitHub lançou recentemente a opção de ter repositórios privados para projetos com até 3 colaboradores.
O Bitbucket continua sendo uma saída gratuita interessante para projetos com mais colaboradores.

;-)

@@12
Consolidando o seu conhecimento

Chegou a hora de você pôr em prática o que foi visto na aula. Para isso, execute os passos listados abaixo.
No repositório do GitHub que você criou utilizando o seu usuário no curso anterior, clique na aba Issues;
Clique em New issue para criar uma nova issue para o seu projeto;
Defina o título como "Adicionar título na página" e a descrição como "A página contém apenas a lista dos cursos. Senti falta de um título";
Clique em Submit new issue para criar a issue em questão;
Crie um novo usuário no GitHub, que servirá como um colaborador fictítcio (como o exemplo da analura);
Com este novo usuário, vá até o seu repositório original e clique em Fork, para criar uma cópia dele;
Em seu computador, acesse a pasta do projeto como Ana, e execute git pull origin master. Confira que não há este repositório remoto;
Adicione o repositório fork ao projeto da Ana, utilizando git remote add origin {url_do_repositorio};
Execute git pull origin master para trazer todas as alterações para o projeto local da Ana;
Logo após a abertura da tag <body> no HTML, adicione <h1>Cursos de DevOps</h1>;
Execute o comando git config --local user.email "{email}", substituindo {email} pelo e-mail do usuário fictício que você criou no GitHub, para que o autor dos commits esteja correto;
Execute git add index.html e depois git commit -m "Título adicionado", para realizar o commit desta alteração;
Adicione uma quebra de linha logo após o título recém adicionado;
Execute git add index.html e depois git commit -m "Quebra de linha" para realizar o commit desta alteração;
Execute git push origin master para enviar as alterações para o GitHub do usuário fictício;
15.1. Se estiver utilizando Windows, limpe as credenciais do GitHub

15.2. Vá em Painel de Controle --> Contas de Usuário --> Gerenciador de Credenciais --> Credenciais do Windows;

15.3. Encontre a credencial do GitHub e clique em Remover, para excluí-la;

15.4. Execute git push origin master para, agora sim, enviar as alterações para o GitHub do usuário fictício;

Acesse o repositório cópia do seu usuário fictício;
Confira que há alterações que não estão presentes no repositório original;
Clique em New pull request para criar o pedido de envio de alterações do código original;
Analise as alterações, veja a lista de commits, e depois clique em Create pull request para confirmar a criação;
Defina "Adicionando título na página" como título do pull request e "Adicionando um título na página que antes não tinha." como descrição;
Clique em Create pull request para confirmar todos os dados;
Entre novamente como o seu usuário original do GitHub e confira a aba Pull requests em seu repositório;
Clique em Merge pull request e depois em Confirm merge para trazer este pull request para o seu repositório original;
Confira no GitHub que o código no repositório original foi atualizado com as alterações do usuário fictício;
Acesse, na aba Issues, a issue que você criou para adicionar título;
Digite na caixa de comentários "Fechado pelo PR #". Note que abrirá uma caixa mostrando o título do pull request. Clique nela;
Clique no botão Close and comment;
Acesse novamente o GitHub, utilizando o usuário fictício criado no passo 5;
No repositório do seu usuário original, crie uma nova issue com o título "Trocar ul por dl";
Em seu computador, no repositório da Ana, altere as tags <ul> por <dl> e as tags <li> por <dd>;
Execute git add index.html e depois git commit -m "Trocando UL por DL" para realizar o commit desta alteração;
Separe os títulos das descrições dos cursos, deixando o conteúdo da seguinte forma:
<dl>
<dt>Vagrant</dt>
<dd>Gerenciando máquinas virtuais</dd>
<dt>Docker</dt>
<dd>Criando containers sem dor de cabeça</dd>
<dt>Ansible</dt>
<dd>Sua infraestrutura como código</dd>
<dt>Integração Contínua</dt>
<dd>Maturidade e Produtividade no Desenvolvimento de Software</dd>
<dt>Kubernetes</dt>
<dd>Introdução a orquestração de containers</dd>
</dl>COPIAR CÓDIGO
Execute git add index.html e depois git commit -m "Separando os títulos", para realizar o commit desta alteração;
Adicione uma quebra de linha antes de cada título (<dt>);
Execute git add index.html e depois git commit -m "Quebras de linha" para realizar o commit desta alteração;
Execute git log --oneline para verificar que há três novos commits para a última issue criada;
Execute git rebase -i HEAD~3 para analisar quais dos três últimos commits serão mantidos ou unidos ao anterior;
Troque a palavra pick, nas linhas 2 e 3, por um s (de squash) para que ambos sejam unidos ao commit anterior, da primeira linha;
38.1. Se o editor de texto que for aberto for o Vim, para excluir uma palavra, digite dw. Para começar a digitar, aperte i, e então você pode adicionar o s na linha. Para salvar, aperte Esc e depois :x e Enter;

Na nova tela que abrir, altere a mensagem que será atribuida ao novo commit, para algo como "Trocando UL por DL e separando os títulos";
Execute git log --oneline novamente e confira que agora os três commits viraram apenas 1;
Repita os passos do 15 ao 27, trocando as mensagens e a issue pelo que fizer sentido para seu caso.

Opinião do instrutor

Continue com os seus estudos, e se houver dúvidas, não hesite em recorrer ao nosso fórum!

@@13
O que aprendemos?

Nesta aula, aprendemos:
O que são e como utilizar issues
Que as issues podem ser utilizadas para vários propósitos
Reportar problemas
Sugerir melhorias
Solicitar novas funcionalidades
Organizar qualquer coisa que faça sentido para o projeto
Etc
O que são pull requests
Como unir vários commits em um, utilizando o comando git rebase -i
Como enviar e como revisar um pull request no GitHub

@02-Controle avançado de conflitos

@@01
Pegando um commit

Trabalhamos bastante com a parte de GitHub, conversamos sobre projetos open source, vimos o que são issues, pull requests e afins, mas voltando para o conceito de Git, conforme vamos trabalhando, acabamos nos deparando com um cenário que possui uma linha de desenvolvimento master (principal), com vários commits, uma correção de bug, com merge para o master. Porém, temos um release, com a qual estamos trabalhando, cujos commits ainda não trouxemos ao master por não estarem prontos.
Então, não poderemos simplesmente aplicar um merge ou um rebase destes commits; queremos pegar apenas as alterações feitas no segundo commit, pois precisaremos deles para algo no master. Poderemos, então, copiar o hash do commit desejado, e trazer manualmente para onde queremos, que seria o branch atual. Para fazermos isto, usaremos git cherry-pick 8f7c801 no Visualizing Git, sendo 8f7c801 o hash.

Reparem que o HEAD, isto é, o local em que estamos, e o estado em que o nosso código está, fica na master. Ao executarmos o comando, o commit é selecionado e trazido para ela. Com isso, podemos buscar e trazer um commit específico. Em seguida, executaremos no Terminal git checkout master para irmos à master e, logados como Vinicius, criaremos um branch pois, tanto no repositório do GitHub quanto no repositório local, já trazemos todas as informações. Verificamos isto com git pull origin master e git pull local master.

Para garantir que o código está atualizado, consultaremos o VS Code. Queremos agora trabalhar em um novo release, em desenvolvimento novo, sendo assim, começaremos criando um novo branch, com git checkout -b novo-release. Quando executamos este comando, passamos a trabalhar neste novo branch automaticamente. Voltaremos ao código no VS Code e substituiremos o h1 por h2, pois futuramente poderemos ter outros cursos, que não de DevOps.

Como já estamos acostumados, commitaremos, antes executando git diff para garantir que alteramos apenas o que queríamos. git add index.html, seguido de git commit -m "h1 -> h2". E como teremos vários cursos de categorias distintas, removeremos "de DevOps da Alura" dentre as tags <title>, mantendo simplesmente "Lista de Cursos". Executaremos git add index.html novamente, e então git commit -m "Simplificando o título".

Entretanto, receberemos outra demanda, sendo necessário voltar ao master para corrigir um bug. Usaremos git checkout master, pois o desenvolvimento do novo release ainda não está pronto. Passaremos a trabalhar a partir do código antigo. Mas para a correção que precisamos fazer, é necessário que tenhamos o h2 no lugar de h1. Assim, poderíamos refazer o trabalho realizado em outro branch, e commitar novamente, contendo uma alteração repetida.

Mas isso não é prático — e como acabamos de aprender, pegaremos um commit específico. Executaremos o comando git checkout novo-release, e então git log --oneline e verificar o commit que queremos, no caso, "h1 -> h2", copiar seu hash, retornar à master com git checkout master e trazer o commit para ela, por meio de git cherry-pick befd28c. Assim, quando pressionamos "Enter", é trazido exatamente um único commit, aquele que selecionamos.

No VS Code, teremos o título inalterado, mas o h2 estará lá, substituindo o h1 anterior. Caso terminemos o desenvolvimento do novo release e queiramos trazê-lo de volta à master, ou seja, fazer um rebase do novo release para a master, não teremos este conflito, e o Git terá um trabalho a menos para realizar porque uma das alterações já terá sido implementada.

Iremos fazê-lo, portanto, com git rebase novo-release, e verificaremos no VS Code que o título foi alterado como gostaríamos, sendo que o Git teve um único trabalho a ser realizado. Com isso, passamos a entender o conceito de trazer um único commit, e entendemos que o Git não tentará refazer um trabalho.

Agora, imaginemos que, durante o desenvolvimento do código queiramos saber quando h2 esteve como h1, ou seja, encontrar um estado específico da aplicação. Poderíamos utilizar git log --oneline para analisar as mensagens de commits até encontrar o que buscamos, mas se tivéssemos um histórico muito mais extenso, um projeto que levou meses para ser desenvolvido, por exemplo, esta opção se tornaria inviável.

Entenderemos e conversaremos sobre isso adiante!

@@02
Cherry-pick

No último vídeo, vimos como podemos trazer um único commit específico de outra branch para a branch em que estamos trabalhando.
Em que caso faz sentido trazer um commit específico para a branch atual?

Quando queremos copiar o trabalho do colega
 
Alternativa correta
Quando um bug que afeta a branch atual já foi solucionado em outra branch
 
Alternativa correta! Se uma implementação é necessária em sua branch e já foi feita em outra branch, pode fazer sentido trazer um commit específico, utilizando o git cherry-pick.
Alternativa correta
Quando queremos fazer o merge commit a commit

@@03
Encontrando bugs

Suponhamos que alguém da nossa equipe sobrescrevesse uma alteração que realizamos, modificando o título de "Lista de Cursos" para "Lista de Cursos de DevOps", inclusive commitando a alteração, e que, ainda, uma terceira pessoa da equipe, sabendo que esta alteração não deveria ter sido feita, modificasse o texto para "Lista de Cursos da Alura", commitando em seguida. Além disso, outra pessoa teria alterado o título depois de tudo isso, para "Cursos da Alura", e mais alguém voltaria o texto para "Lista de Cursos".
Muitas modificações foram feitas no título, e agora queremos encontrar o momento exato que determinada alteração foi aplicada. Isto quer dizer que queremos voltar ao estado em que o título esteve como "Lista de Cursos da Alura", por exemplo. Executando git log --oneline, notaremos que as mensagens de commits não são muito significativas e não nos ajudam nisso.

Seria necessário indicarmos ao Git que ele terá que buscar, dentre determinados commits — como os cinco últimos, por exemplo —, e ele teria que passar por cada um deles. Esta feature é chamada de bisect, e para executá-la digitaremos git bisect start, o que inicializará a busca do lado do Git. Inicialmente, é preciso informar a ele um estado, ou commit cuja parte do código que queremos não esteja boa, no caso, o título deverá ser "Lista de Cursos da Alura".

Vamos executar git bisect bad HEAD, e em seguida devemos informar o estado em que possivelmente estava bom, isto é, a partir de onde ele irá buscar o commit desejado. Então, copiaremos o hash referente à primeira alteração de título, e digitaremos git bisect good c17076a. Estes serão os limites da busca feita pelo Git. Obteremos a mensagem de que há uma revisão a mais para testarmos depois desta, e ele nos mostrará o estado de "Mudando título".

Neste estado, o título será aquele que queremos, e se ele ainda não tivesse encontrado a alteração desejada, continuaríamos executando git bisect bad, mas no nosso caso, como já estaremos no estado desejado, usaremos git bisect good. Após esta revisão, se tudo estiver bem, não precisaremos mais fazer nada. Para finalizar a busca, uma vez que o Git já nos entregou o hash e a descrição do commit, usaremos git bisect reset, com o qual voltaremos à master.

Com o hash do commit, poderíamos desfazer a alteração, analisar o porquê da inclusão dela, perguntar o que aconteceu à pessoa que realizou o commit. Para verificarmos todas as alterações referentes ao commit, aplicaremos o comando git show seguido do hash. Para reverter esta ação, pode-se utilizar git revert juntamente ao hash.

Notem como é relativamente fácil encontrar um commit em que uma alteração específica foi implementada, sem que precisássemos, por exemplo, usar o git checkout ou git show em cada um dos commits existentes. E se, a partir do momento em que encontramos uma alteração, ou quando ainda estivermos analisando o log de commits, quisermos saber quem foi o responsável por determinado commit, será que o GitHub consegue nos ajudar?

@@04
Bisect

No último vídeo, nós utilizamos o git bisect para encontrar determinado ponto na história do código em que alguma alteração foi introduzida. Fizemos isso, informando os estados do commit (se estava "bom" ou "ruim").
Para que o git bisect pode ser útil?

Encontrar o culpado por um bug
 
Alternativa correta
Para atualizar a nossa linha do tempo
 
Alternativa correta
Para encontrar o commit em que um bug foi introduzido
 
Alternativa correta! Encontrando o exato commit em que determinado bug foi introduzido, podemos revertê-lo ou até mesmo tentar entender o motivo daquele bug ter sido introduzido.

@@05
Encontrando o culpado

Vimos uma forma de encontrar bugs, muito sobre open source, temos trabalhado de forma bastante profissional com o Git, mas há uma pequena dúvida: queremos saber quem é o responsável por adicionar a linha <h2>Cursos de DevOps</h2> em nosso arquivo, pois lembramos que anteriormente o h2 era h1. Eu estava de férias na época e não sabemos o motivo desta alteração, e queremos questioná-lo sobre.
O Git permite um comando denominado git blame seguido do nome de um arquivo, a partir do qual são exibidos os responsáveis por cada uma das linhas do arquivo. No início do primeiro curso de Git ainda não tínhamos configurado um nome, e é por isto que os logs iniciais estão vazios, porém, isto não será um problema, pois a linha que nos interessa é facilmente identificável, sendo o responsável Vinicius Dias.

E esta alteração foi introduzida no commit befd28c3, e com isto conseguimos entender quem fez uma alteração em determinada linha, e conseguimos contatar a pessoa, no caso, Vinicius. Também constam informações acerca do horário e data dos commits. No entanto, fica o adendo de que muitas vezes este comando é mal utilizado por pessoas que querem encontrar um "culpado" por um bug.

Mas não é recomendado que se trabalhe desta maneira — não se deve apontar culpados. Se você estiver utilizando git blame com este propósito, é mais interessante abrir um diálogo com a pessoa, e sugerir melhorias ou resoluções do problema. Também pode-se utilizar este método para aprender mais com a pessoa que implementou algo, por exemplo.

Mais adiante veremos algumas ferramentas que talvez auxiliem na visualização desta lista. Continuando, agora que já conversamos bastante sobre open source, controle avançado de versões para escolhermos um commit específico, nosso branch, por exemplo, para conseguirmos encontrar bugs ou a pessoa responsável por cada linha do nosso arquivo, está na hora de trabalharmos de forma ainda mais profissional.

Não podemos, por exemplo, continuar executando todo o nosso código na master. Qual o papel da master no projeto, em um contexto mais amplo? Vamos conversar sobre branches, organização, e alguns padrões a seguir.

https://cursos.alura.com.br/course/git-github-controle-de-versao

@@06
Blame

Com o git blame, podemos ver quem é o responsável por cada linha no código.
Para que isso pode ser útil?

Para saber para quem perguntar sobre determinado bloco de código que não entendemos
 
Alternativa correta! Com o git blame, nós podemos saber quem é o responsável por determinada linha ou bloco de código que nós não entendemos, e com isso sabemos com quem tirar a dúvida!
Alternativa correta
Para encontrar o culpado por um bug
 
Alternativa correta
Para desfazer uma alteração

@@07
Consolidando o seu conhecimento

Chegou a hora de você pôr em prática o que foi visto na aula. Para isso, execute os passos listados abaixo.
Acesse a pasta do seu repositório no computador;
Execute git checkout master para trabalhar na branch master;
Execute git pull origin master e git pull local master para garantir que você está com o código atualizado e sincronizado com os dois repositórios remotos;
Execute git checkout -b novo-release para passar a trabalhar em um nova branch, chamada novo-release;
Substitua as tags <h1> por <h2> no código do arquivo index.html;
Execute git add index.html e git commit -m "h1 -> h2" para commitar esta alteração;
Confira o hash do commit que foi mostrado na saída do comando. Copie ele;
Altere o título do arquivo (na tag <title>) para "Lista de cursos";
Execute git add index.html e git commit -m "Simplificando o título" para commitar esta alteração;
Execute git checkout master para voltar a trabalhar na branch master (pois há um bug que você deve corrigir antes de continuar o trabalho do seu novo release);
Execute o comando git cherry-pick {hash} para trazer um commit para a branch master. Substitua {hash} pelo hash que foi copiado no passo 6;
Confira que apenas a alteração desejada foi aplicada no master, e não toda a branch novo-release;
Execute o comando git rebase novo-release e confira que o Git executa apenas um trabalho, embora hajam dois commits na nova branch, pois um já foi trazido para o master;
Altere o título da página (na tag <title>) para "Lista de cursos de DevOps";
Execute git add index.html e git commit -m "Adicionando DevOps no título" para commitar esta alteração;
Altere o título da página (na tag <title>) para "Lista de cursos da Alura";
Execute git add index.html e git commit -m "Mudando título" para commitar esta alteração;
Altere o título da página (na tag <title>) para "Cursos da Alura";
Execute git add index.html e git commit -m "Mexendo no título" para commitar esta alteração;
Altere o título do arquivo (na tag <title>) para "Lista de cursos";
Execute git add index.html e git commit -m "Título alterado" para commitar esta alteração;
Execute o comando git bisect start para informar ao Git que você vai iniciar uma busca por determinada alteração;
Execute o comando git bisect bad HEAD para informar que o estado atual do código está "ruim", ou seja, o título não está no estado que você quer;
Executando git log --oneline, copie o hash do commit com a mensagem "Simplificando o título";
Execute o comando git bisect good {hash}, substituindo {hash} pelo hash copiado no passo anterior, para informar que o estado atual do código está "bom", ou seja, o título está no estado que você quer;
Confira no código que agora o título está como você quer;
Execute git bisect good para informar ao Git que neste commit o código ainda está como você quer;
Confira no código que agora o título não está mais como você quer;
Execute git bisect bad para informar ao Git que neste commit o código não está mais como você quer;
Note que o Git encontrou o exato commit onde o título deixou de estar no estado em que você quer;
Execute git bisect reset para indicar que você finalizou a busca;
Execute o comando git show {hash}, substituindo {hash} pelo hash conferido no passo 30. Veja que é exatamente a alteração que você estava buscando;
Para reverter esta alteração, execute git revert {hash}, substituindo {hash} pelo hash conferido no passo 30. Resolva quaisquer conflitos que possam ter sido encontrados;
Execute git blame index.html e confira o responsável por cada linha do arquivo.

Opinião do instrutor

Continue com os seus estudos, e se houver dúvidas, não hesite em recorrer ao nosso fórum!

@@08
O que aprendemos?

Nesta aula, aprendemos:
Que o comando git cherry-pick pode trazer um commit específico para a branch atual;
Como encontrar o commit em que determinada alteração foi aplicada, utilizando o git bisect;
Como encontrar o responsável por determinada linha ou bloco de código, utilizando o git blame;
Que jamais devemos apontar um culpado por determinado bug. Uma equipe deve ser unida e se ajudar;
Que o comando git show {hash} mostra todas as alterações aplicadas pelo commit com o hash informado.

#### 21/07/2023

@03-Estratégias de branching

@@01
Master e produção

Atualmente nosso projeto conta com mais de um branch. Mas será que teremos Git no servidor que rodará o código, quando ele for para a produção? Caso a resposta seja "sim", o nosso código precisará estar na master? Em qual branch este código precisará estar?
Vamos executar git log --graph para visualizarmos um gráfico contendo uma linha maior, que em determinado momento passa a ter uma linha de desenvolvimento extra, que vem de um pull request de "analura", a Ana. Em outro momento, temos linhas um pouco mais confusas, por conta de um pull request que dá início a outra linha de desenvolvimento, com merge para a master também, ou seja, temos vários branches e, no fim de tudo, há uma linha, que é do branch master.

O branch master é o local que abrigará todo o trabalho, isto é, o código que irá para a produção, que está finalizado e pronto para ir ao ar. Ter o Git instalado no servidor é uma escolha pessoal da equipe de desenvolvimento ou infra. O importante é que o código, a cópia dos arquivos que precisam estar lá, tem que ser o mesmo dos arquivos contidos pelo branch master.

Esta não é uma regra estrita, e sim uma convenção muito bem seguida e adotada. Utilizamos o branch master como linha principal de desenvolvimento, para onde vão os trabalhos realizados. Se os trabalhos chegam prontos, significa que temos outros branches. Portanto, o código não deve ser desenvolvido no master, pois ele não pode ser editado diretamente no master.

Caso esta recomendação seja ignorada, o código continuará funcionando, inclusive muitas pessoas commitam diretamente na master, porém, a boa prática recomenda que se desenvolva em uma branch à parte para que na nossa master só estejam commits prontos e testados. Enquanto estamos desenvolvendo e commitando, sabemos que não está tudo bem testado ou com a qualidade garantida.

E então conversaremos a seguir sobre quais branches devemos criar.

@@02
Log visual

Durante o vídeo, nós visualizamos o nosso log de commits de uma forma um pouco mais visual, onde as diferentes branches são representadas por linhas separadas.
Qual o comando para exibir o log desta forma?

git log
 
Alternativa correta
git log --graph
 
Alternativa correta! Desta forma, uma representação um pouco mais gráfica do log é exibida na linha de comando.
Alternativa correta
git log --format

@@03
Mais branches

Como comentado anteriormente, é sempre interessante mantermos na master o código pronto para produção. Criaremos outro branch para abrigar as alterações feitas, que enviaremos ao master somente quando estiver pronto. Já temos dois branches que não estão sendo utilizados, novo-release e titulo, que removeremos com git branch -d seguido do título.
Caso haja algum conflito, como o branch a ser deletado estar à frente do branch atual, ou seja, se novo-release tivesse alguns commits à frente do master, teríamos que utilizar git branch -D novo-release, com "D" em maiúsculo.
Criaremos um branch de desenvolvimento por meio de git branch development, em que começaremos a testar nossas features, após executarmos git checkout development. Em seguida, partindo deste novo branch criaremos outro, para acrescentarmos uma nova lista de cursos, com git checkout -b feature/lista-cursos-cloud.

No VS Code, digitaremos o seguinte, abaixo da primeira lista de cursos:

<h2>Cursos de Cloud</h2>
<dl>
    <dt>Amazon EC2</dt>
    <dd>Faça um deploy da sua webapp com alta disponibilidade e escalabilidade.</dd>

    <dt>Amazon S3</dt>
    <dd>Manipule e armazene objetos na nuvem</dd>
</dl>COPIAR CÓDIGO
Feito isto, criaremos um commit com git add index.html e git commit -m "Cursos de EC2 e S3 adicionados". Depois, adicionaremos mais dois cursos:

<h2>Cursos de Cloud</h2>
<dl>
    <dt>Amazon EC2</dt>
    <dd>Faça um deploy da sua webapp com alta disponibilidade e escalabilidade.</dd>

    <dt>Amazon S3</dt>
    <dd>Manipule e armazene objetos na nuvem</dd>

    <dt>Amazon Elastic Beanstalk Parte 1</dt>
    <dd>Container Docker</dd>

    <dt>Amazon ECS</dt>
    <dd>Gerencie Docker na nuvem da AWS</dd>
</dl>COPIAR CÓDIGO
Commitaremos com git add index.html e git commit -m "Cursos de Beanstalk e ECS adicionados". Enquanto estamos desenvolvendo, outra pessoa da equipe estará tratando dos cursos de Linux, então, a partir do branch de desenvolvimento, criaremos outro branch: git checkout -b feature/lista-cursos-linux. No VS Code, acrescentaremos mais estas linhas de código:

<h2>Cursos de Linux</h2>
<dl>
    <dt>Linux I</dt>
    <dd>Conhecendo e utilizando o terminal</dd>

    <dt>Linux II</dt>
    <dd>Programas, processos e pacotes</dd>
</dl>COPIAR CÓDIGO
Executaremos git add index.html e git commit -m "Cursos de Linux I e II adicionados". Voltaremos ao branch de desenvolvimento com git checkout development, e verificaremos a quantidade de branches que temos no momento com git branch, além da master — um com os códigos em desenvolvimento (development), e um branch para cada feature, um para a lista de cursos Cloud e outro para a lista de cursos Linux.

Finalizada a lista de cursos de Linux, poderemos trazê-la para o branch de desenvolvimento, com git merge feature/lista-cursos-linux. Verificaremos se tudo está dentro dos conformes no VS Code, e com git checkout feature/lista-cursos-cloud faremos uma alteração acrescentando mais um curso à lista de cursos de Cloud.

<dt>Google Cloud</dt>
<dd>Deploy de uma aplicação em Spring MVC</dd>COPIAR CÓDIGO
Estando no branch da lista de cursos de Cloud, executaremos git add index.html e git commit -m "Curso de Google Cloud adicionado". Por fim, iremos ao branch de desenvolvimento por meio de git checkout development e faremos um merge com git merge feature/lista-cursos-cloud. Obteremos, porém, um conflito indicando que, no trabalho atual, temos dois branches distintos, um com lista de cursos Linux e outro com a lista de cursos de Cloud.

Como queremos manter ambos, simplesmente corrigiremos o código manualmente. Notem como foi tranquilo lidar com este conflito por estarmos lidando com branches separados, o que traz todas as features de uma só vez para que possamos resolvê-lo. Adicionaremos o index.html e commitaremos para que se continue o merge.

Assim, em nosso branch de desenvolvimento temos as listas de cursos Cloud e Linux, e um branch para cada feature. Poderemos testar como estas duas features desenvolvidas separadamente funcionam em conjunto. Porém, ao voltarmos ao código master com git checkout master, encontraremos um bug, pois há o título "Lista de Cursos da Alura", sendo que poderemos ter cursos presenciais da Caelum.

Neste caso, por mais urgente que seja a correção de um bug, não devemos commitar na master. Portanto, criaremos git checkout -b hotfix/v0.1.1 a partir da master, em que "hotfix" remete a um "conserto rápido de um bug", indicando também a versão em que será implementada esta correção.

Em seguida, trocaremos "Lista de Cursos da Alura" para "Lista de Cursos" manualmente, em index.html, e executaremos git add index.html e git commit -m "Removendo nome da Alura do título" no Terminal. Por se tratar de um bug, não passaremos ao branch de desenvolvimento, e sim à produção, com git checkout master e git merge hotfix/v0.1.1. Como temos uma nova versão a ser lançada, utilizaremos o comando git tag -a v0.1.1. A mensagem para a tag será "Versão com correção no título".

Neste vídeo, criamos dois branches de desenvolvimento, de features, um para trazer todas as features, e um de correção de bug, que enviamos diretamente à master. Agora, é preciso trazer todas as correções ao branch de desenvolvimento, com git merge hotfix/v0.1.1 após git checkout development. Temos, então, tudo o que é necessário para lançarmos uma nova versão no branch de desenvolvimento.

Para isto, é necessário realizarmos alguns testes, por isso criaremos um branch chamado "release", de versão 0.2: git checkout -b release/v0.2.0, com a correção aplicada na versão anterior e, além disso, novas listas. Entretanto, esquecemos de incluir cursos de Shell Script na lista dos cursos de Linux! Faremos isto no branch de release, pois a feature já foi desenvolvida. Teremos:

<h2>Cursos de Linux</h2>
<dl>
    <dt>Linux I</dt>
    <dd>Conhecendo e utilizando o terminal</dd>

    <dt>Linux II</dt>
    <dd>Programas, processos e pacotes</dd>

    <dt>Shell Script I</dt>
    <dd>Começando seus scripts de automação de tarefas</dd>

    <dt>Shell Script II</dt>
    <dd>Fazendo monitoramento, agendando tarefas e backup</dd>
</dl>COPIAR CÓDIGO
Realizaremos o commit no branch desta release, por meio de git add index.html, git commit -m "Corrigindo bug: Cursos de shell faltantes". A release estará pronta, o código estará compilando sem problemas, então poderemos colocá-lo em produção, mas antes disto precisaremos enviá-lo para a master, com git checkout master e git merge release/v0.2.0.

Assim, no nosso código de produção teremos a correção do título, as novas listas, referentes aos cursos de Linux e Cloud, e a correção da release. E se temos uma nova versão, teremos uma nova tag — executaremos git tag -a v0.2.0 -m "Novas listas de cursos adicionadas". Ao executarmos git branch, verificaremos a existência do branch que terá nosso estado mais próximo da versão futura, junção de todos os branches de feature, as quais se juntarão ao branch de desenvolvimento.

Quando tudo isto estiver mais testado e próximo de ir à produção, criamos um branch de release para passar à equipe de qualidade para que eles possam testar, e se houver algum problema muito sério, pode-se resolver diretamente no branch de release. Mas se surgir um bug de algo que está em produção, precisaremos corrigir a partir da master, criando um novo branch para correção, e enviando de volta para a master e para o branch de desenvolvimento, que precisa estar sempre atualizado.

@@04
Git Flow

Esta forma de organização de branches que facilita a resolução de conflitos, inclusive para que bugs repetidos não aconteçam, é denominada Git flow, bem representada em alguns gráficos, como este:


Nele, o branch master só serve para receber os commits prontos para ir à produção, a partir dos quais geramos as tags. Existe também o branch de desenvolvimento (Develop), de que serão criados os branches de feature, ou seja, funcionalidades novas, os quais serão enviados de volta ao branch de desenvolvimento em dado momento. Quando o branch de desenvolvimento tiver todas as features, criamos um branch de release, isto é, quando começa o processo de lançarmos uma nova versão.

E no branch de release somente corrigimos os bugs relacionados ao release em si. Ou seja, sempre que um bug for corrigido, é preciso enviá-lo de volta ao branch de desenvolvimento, pois outras features podem se aproveitar desta correção. E no final, tudo estando corrigido, irá para a master para receber uma tag. Caso ocorra algum problema em produção, ou seja, no branch master, um branch de hotfix precisará ser criado e, sempre que corrigido, tudo é enviado à master, e em seguida, também para o branch de desenvolvimento. Claro, pois todas as features se aproveitarão desta correção.

Há outro gráfico, que envolve vários branches de features, ou seja, de funcionalidades, um geral, de desenvolvimento, branches de release, ou seja, versões a serem lançadas, de hotfixes e o master. Portanto, são os mesmos branches dispostos em top down, em vez de horizontalmente. Tudo começa na master, de onde se cria um branch de desenvolvimento, até que surja a necessidade de uma nova funcionalidade, e para isto, são criados branches.

Enquanto isso, quando se encontra um bug em produção, é criado um branch a partir da master, o bug é corrigido e a correção é enviada de volta à master, sendo criada uma tag de correção. Feito isso, a correção é enviada ao branch de desenvolvimento, para que todas as features, quando forem enviadas ao branch de desenvolvimento, tenham a correção implementada.

Quando o desenvolvimento de uma feature for finalizado, podemos começar o processo de desenvolvimento da release. Para tal, criamos um branch de release, dentro do qual corrigimos bugs específicos dela. Se o bug em específico não afeta esta release, não mexeremos nele; se é uma funcionalidade nova, não é este o momento de mexermos nela.

Conforme os bugs são corrigidos, os branches de desenvolvimento são atualizados. Quando uma nova feature é finalizada, ela é enviada ao branch de desenvolvimento, de onde é enviada para o branch de release. Quando todos os testes forem finalizados e o branch de release estiver pronto, atualizamos o branch de desenvolvimento enviando a correção também para o branch master, e criando uma nova tag, ou versão.

Este fluxo denominado Git flow pode ajudar equipes em projetos grandes, diminuindo o número de conflitos, organizando o ciclo de desenvolvimento de uma versão, algo bem interessante. Quando estamos desenvolvendo sozinhos, não parece muito prático, mas quando estamos em uma equipe grande, isso faz toda a diferença. Claro, esta não é a única estratégia de organização de fluxo existente.

Atualmente, na empresa em que trabalho, por exemplo, lidamos com um projeto de cerca de vinte anos, e temos um sistema que gerencia as demandas, chamadas tickets, e cada uma delas vira um branch. A funcionalidade ou correção que gerou o novo branch se desloca para um branch específico de code review (revisão de código) para garantir que o código esteja correto, passando ao branch de testes, em que a equipe de qualidade analisa se todo o restante do sistema continua funcionando com esta implementação, e caso positivo, se seguirá ao branch de release, específica da versão.

Quando a versão estiver finalizada, é realizado o merge para o master. Então, é um pouco diferente, embora se baseie em algo similar, mas exemplifica a possibilidade de não termos que necessariamente aplicar todos os branches e conceitos do Git flow, e sim somente aqueles que fazem sentido para o trabalho e equipe.

É verdade que o trabalho de lidar com vários branches é bastante manual, e é por isso que conversaremos a seguir sobre ferramentas que podem nos ajudar com isso!

https://caelum-online-public.s3.amazonaws.com/1276+-+Git+e+Github+pt+2/transcri%C3%A7%C3%A3o/20180412-git-flow.png

@@05
Várias branches

Aprendemos de forma bem resumida sobre a estratégia de organização de branches, chamada Git Flow.
Quais as branches presentes nesta estratégia?

Master, Develop, Branches de feature, Branches de Hotfix e Branches de release
 
Alternativa correta! Cada uma das branches tem um propósito bem definido e nos ajudam a manter o nosso controle de versões bem organizado.
Alternativa correta
Master e Develop
 
Alternativa correta
Master, Ticket, Testing, Release

@@06
Consolidando o seu conhecimento

Chegou a hora de você pôr em prática o que foi visto na aula. Para isso, execute os passos listados abaixo.
Execute git log --graph e confira que, embora haja várias linhas de desenvolvimento, tudo começa e termina na linha da branch master;
Execute o comando git branch -d titulo para remover a branch titulo;
Execute o comando git branch -D novo-release para remover a branch novo-release, mesmo que ela tenha commits à frente do master;
Execute o comando git branch development para criar um nova branch de desenvolvimento chamado development;
Execute o comando git checkout development para passar a trabalhar na branch development;
Execute o comando git checkout -b feature/lista-cursos-cloud para criar um nova branch, chamada feature/lista-cursos-cloud;
Adicione o seguinte conteúdo após a lista de cursos de DevOps:
<h2>Cursos de Cloud:</h2>
<dl>
 <dt>Amazon EC2</dt>
 <dd>Faça um deploy da sua webapp com alta disponibilidade e escalabilidade.</dd>

 <dt>Amazon S3</dt>
 <dd>Manipule e armazene objetos na nuvem</dd>
</dl>COPIAR CÓDIGO
Execute git add index.html e git commit -m "Cursos de EC2 e S3 adicionados" para commitar esta alteração;
Adicione a esta lista os dois seguintes cursos:
 <dt>Amazon Elastic Beanstalk Parte 1</dt>
 <dd>Container Docker</dd>

 <dt>Amazon ECS</dt>
 <dd>Gerencie Docker na nuvem da AWS</dd>COPIAR CÓDIGO
Execute git add index.html e git commit -m "Cursos de Beanstalk e ECS adicionados" para commitar esta alteração;
Execute git checkout development para voltar para a branch de desenvolvimento;
Execute git checkout -b feature/lista-cursos-linux para passar a trabalhar em um nova branch, chamada feature/lista-cursos-linux;
Adicione o seguinte conteúdo após a lista de cursos de DevOps:
<h2>Cursos de Linux:</h2>
<dl>
<dt>Linux I</dt>
<dd>Conhecendo e utilizando o terminal</dd>

<dt>Linux II</dt>
<dd>Programas, processos e pacotes</dd>
</dl>COPIAR CÓDIGO
Execute git add index.html e git commit -m "Cursos de Linux I e II adicionados" para commitar esta alteração;
Execute git checkout development para voltar para a branch de desenvolvimento;
Execute o comando git branch para conferir quantas e quais branches você têm criadas atualmente;
Execute o comando git merge feature/lista-cursos-linux para trazer os cursos de Linux para a branch de desenvolvimento;
Execute o comando git checkout feature/lista-cursos-cloud para voltar à branch feature/lista-cursos-cloud;
Adicione, à lista de cursos de Cloud, o seguinte curso:
<dt>Google Cloud</dt>
<dd>Deploy de uma aplicação em Spring MVC</dd>COPIAR CÓDIGO
Execute git add index.html e git commit -m "Curso de Google Cloud adicionado" para commitar esta alteração;
Execute git checkout development para voltar para a branch de desenvolvimento;
Execute o comando git merge feature/lista-cursos-cloud para trazer os cursos de Cloud para a branch de desenvolvimento;
Resolva o conflito mantendo as duas listas novas de cursos;
Execute git add index.html e git commit para continuar o processo de merge;
Volte para a branch master com o comando git checkout master;
Trabalhe em um nova branch, chamada hotfix/v0.1.1, utilizando o comando git checkout -b hotfix/v0.1.1;
Altere o título da página (na tag <title>) para "Lista de cursos";
Execute git add index.html e git commit -m "Removendo o nome da Alura do título" para commitar esta alteração;
Volte para a branch master, com o comando git checkout master;
Una o trabalho do hotfix, com o comando git merge hotfix/v0.1.1;
Crie uma nova tag que representa uma nova versão, utilizando o comando git tag -a v0.1.1 -m "Versão com correção no título";
Vá para a branch de desenvolvimento com git checkout development;
Traga a correção do bug com git merge hotfix/v0.1.1;
Crie um nova branch, chamada de release/v0.2.0, com o comando git checkout -b release/v0.2.0;
Adicione os dois seguintes cursos na lista de cursos de Linux:
<dt>Shell Script I</dt>
<dd>Começando seus scripts de automação de tarefas</dd>COPIAR CÓDIGO
<dt>Shell Script II</dt>
<dd>Fazendo monitoramento, agendando tarefas e backup</dd>COPIAR CÓDIGO
Execute git add index.html e git commit -m "Corrigindo bug: Cursos de Shell faltantes" para commitar esta alteração;
Volte para a branch master, com o comando git checkout master;
Una todo o trabalho referente à nova release, com git merge release/v0.2.0;
Crie uma nova tag que representa uma nova versão, utilizando o comando git tag -a v0.2.0 -m "Novas listas adicionadas";
Execute o comando git branch e confira todos as branches criadas neste processo;

Opinião do instrutor

Continue com os seus estudos, e se houver dúvidas, não hesite em recorrer ao nosso fórum!

@@07
O que aprendemos?

Nesta aula, aprendemos:
Que é uma convenção bem seguida que a branch master tenha apenas os commits prontos para ir para produção;
Que não é interessante realizar trabalho e commitar diretamente na branch master;
Como remover uma branch:
git branch -d {nome_branch} remove uma branch que já tem seu trabalho unido à branch atual;
git branch -D {nome_branch} remove uma branch mesmo que os commits desta branch ainda não estejam na branch atual, ou seja, força a remoção;
Um pouco do processo chamado de Git Flow:
Entendemos que o estado do código representado pela branch master deve ser o mesmo que estará em produção
Vimos que deve haver uma branch de desenvolvimento (comumente chamado de develop), onde todas as funcionalidades e correções devem ser muito bem testadas antes de ir para produção (master)
Vimos que cada funcionalidade deve ser feita em uma branch separada, e que é comum que esta branch tenha feature/ como prefixo
Aprendemos também que bugs normalmente são corrigidos em branches separadas, com o prefixo hotfix/
Além disso, branches específicas para cada release são criadas para realizar os testes e correções de bugs específicos