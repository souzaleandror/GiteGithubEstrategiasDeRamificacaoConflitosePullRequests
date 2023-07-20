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

