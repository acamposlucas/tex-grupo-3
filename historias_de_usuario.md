# Histórias

Como usuário quero ver em quais lojas e produtos posso usar meus cupons para
avaliar a possibilidade de compra

-   Como usuário quero ter acesso a meu perfil e poder acompanhar meu histórico
    de compras e a situação dos meus cupons 13

# Histórias

| id  | história                                                                                                                                                          | pontuação |
| :-: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------: |
|  1  | Como usuário quero fazer um cadastro no app para adquirir cupons e ser notificado sobre novos descontos                                                           |         8 |
|  2  | Como usuário quero ver em quais lojas e produtos posso usar meus cupons para avaliar a possibilidade de compra                                                    |        13 |
|  3  | Como usuário quero ter acesso a meu perfil e poder acompanhar meu histórico de compras e a situação dos meus cupons                                               |        13 |
|  4  | Como gestor devo conseguir administrar cupons e vouchers aos clientes                                                                                             |        21 |
|  5  | Como desenvolvedor devo fazer a integração entre a compra finalizada pelo usuário e sua carteira digital para que seja possível transformar esse valor em voucher |        34 |
|  6  | Como desenvolvedor devo criar o layout do aplicativo                                                                                                              |        34 |
|     | Pontuação Total                                                                                                                                                   |       123 |

## Story #1 - Cadastro Cliente

|Descritivo  | `Como usuário quero me cadastrar no aplicativo para ter acesso aos cupons`   |
| ------- | -------- |
|Tarefas  | `Usuário é redirecionado para página de cadastro`   |
|		  | `Usuário preenche dados com campos nome, CPF, e-mail, senha e confirmação de senha`   |
|		  | `Usuário clica em cadastrar e faz autenticação para confirmação de conta cadastrada`   |
|		  | `Inserir novo cadastro no banco de dados caso usuário não tenha um cadastro`   |
|		  | `Se usuário tiver um cadastro, notifica-lo e exibir opção para redefinição de senha`   |
|		  | `Usuário é redirecionado para página principal após cadastro`   |
|		  | `Usuário tem acesso aos cupons na tela, podendo selecionar para usar em uma loja de sua preferência`   |
|		  | `Usuário pode adicionar cupons em sua conta para poder usá-los`   |
|		  | `Na home page entrar no ícone "meu perfil", usuário cadastrado pode ver: cupons disponíveis, inválidos e expirados para acompanhar o seu histórico de consumo`   |
|		  | `Ao escolher cupom usuário é redirecionado para o site da loja`   |
|		  | `Usuário é notificado sobre novos cupons atráves da barra de notificações do celular ou e-mail e whatsapp se for de sua preferência`   |


## User story 2

| Story #2   | Lojas e produtos para usar o cupom                                                                                                                                                                                                                                                                                                                                                                                                    |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descritivo | Como usuário quero ver a disponibilidade de produtos e lojas que aceitam o meu cupom de desconto                                                                                                                                                                                                                                                                                                                                      |
| Tarefas    | <ul><li>O usuário pesquisará seu cupom de desconto.</li> <li>O usuário verifica se o cupom é aplicável ao produto e a loja que está disponível.</li> <li> O usuário clica em obter cupom. </li> <li>O sistema verificará se o cupom está válido ou expirado. Se válido, o usuário é redirecionado para a loja parceira, se não exibe mensagem "Cupom expirado"</li><li> O usuário finaliza a compra na loja parceira com o cupom</li> |

## User story 3

| Story #3   | Perfil do Usuário                                                                                                                                                                                                                                                                                                                                                                                                                                |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Descritivo | Como usuário quero ter acesso a meu perfil e poder acompanhar meu histórico de compras e a situação dos meus cupons.                                                                                                                                                                                                                                                                                                                             |
| Tarefas    | <ul><li>O Usuário deve logar na sua conta.</li> <li>O Usuário clicar no icone do perfil, onde será redirecionado para a pagina de usuário.</li> <li> O Usuário terá acesso aos seus dados pessoais. </li> <li>O Usuário terá acesso ao seus cupons.</li><li> O Usuário terá acesso ao seu historico de cupons.</li><li> No seu perfil o usuário terá acesso ao seus dados de cadastro, seu historico de cupons usados e seus cupons ativos.</li> |

## User story 4

| Story #4   | Administração de Cupons                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Descritivo | Eu, como gestor, devo conseguir administrar cupons e vouchers para o consumo dos clientes                                                                                                                                                                                                                                                                                                                                                                    |
| Tarefas    | <ul><li>Gestor acessa o aplicativo, sendo encaminhado para a página "Home".</li><li>Gestor clica no botão de "Login" e é encaminhado pra página "Login".</li><li>Gestor preenche os campos de usuário, senha, confirmação de senha e opção "Não sou um robô" (CAPTCHA?).</li><li>Gestor clica em "Entrar".</li><li>Sistema faz a validação de campos vazios. Impede o acesso se não forem todos preenchidos.</li><li>Sistema verifica se o usuário (gestor) existe no banco de dados e as informações estão corretas.- Sistema verifica se o usuário (gestor) existe no banco de dados e as informações estão corretas.</li><li>Gestor é encaminhado para sua página de perfil / perfil da loja.</li><li>Gestor clica no botão "Cadastrar cupom".</li><li>Gestor é encaminhado para página de cadastro de cupom.</li><li>Gestor preenche os campos de nome do cupom, valor máximo do cupom, número de cupons para gerar, valor de pontuação(?), categoria de produtos para ser utilizado, link da loja parceira e data de expiração.</li><li>Gestor clica em "Criar cupom".</li><li>Sistema checa se este cupom já existe. A ação é cancelada caso exista.</li><li>Gestor é encaminhado para sua página de perfil / perfil da loja.</li><li>Gestor clica no botão "Cadastrar voucher".</li><li>Gestor é encaminhado para página de cadastrar voucher.</li><li>Gestor preenche os campos de nome do voucher, número de vouchers para gerar, valor de pontuação(?), valor máximo do voucher, número (ou valor) de cupons necessários para gerar o voucher, categoria de produtos para ser utilizado, link da loja parceira e data de expiração.</li><li>Gestor clica em "Criar voucher".</li><li>Sistema checa se este voucher já existe. A ação é cancelada caso exista.</li><li>Gestor é encaminhado para sua página de perfil / perfil da loja.</li><li>Em sua página de perfil, cada cupom/voucher aparece como um "card" com informações sobre seu uso (% resgatado e % utilizado) e um botão de excluir.</li><li>Gestor clica no botão "Excluir cupom" que fica embaixo de cada cupom criado.</li><li>Gestor clica no botão "Excluir voucher" que fica embaixo de cada voucher criado.</li></ul> |


## User story 5

| Story #5   | VOUCHERS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Descritivo | Como desenvolvedor devo fazer a integração entre a compra finalizada pelo usuário e sua carteira digital para que seja possível transformar esse valor em voucher                                                                                                                                                                                                                                                                                                                                                                    |
| Tarefas    | <ul><li> sistema deve direcionar usuário ao site da loja após ativar o cupom desejado</li><li> sistema deve receber a confirmação da compra feita pelo usuário no site da loja utilizando o cupom </li><li> Após a confirmação, sistema deve adicionar a pontuação de cupons utilizados à conta do usuário </li><li> sistema deve adicionar os vouchers de acordo com a pontuação acumulada pelo usuário </li><li> sistema deve permitir ao usuário utilizar os vouchers adquiridos para novas compras nas lojas parceiras</li></ul> |
