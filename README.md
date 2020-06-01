![Documentação técnica BeWatch - 2018/2020](https://www.diogenesjunior.com.br/docs/bewatch.jpg)

> Documentação técnica BeWatch WordPress/WooCommerce theme Janeiro de 2018 à Maio de 2020


<h2 align:"center">Informações técnicas e manual do desenvolvedor BeWatch.</h2>


> Atenção:
<p>
Essa documentação irá abordar apenas os itens que foram feitos originalmente para o tema, baseados no desenvolvimento feito por Diogenes Junior. Alguns itens dentro do tema foram feitos por outros programadores, e não temos informações suficiêntes sobre o porque de algumas escolhas deles, ou suas funcionalidades, bugs e outras características.
</p>


> Acesso aos arquivos:
<p>
Todos os arquivos de código fonte são privados e devem ser solicitados diretamente à equipe BeWatch no e-mail robertachechetto@gmail.com.
</p>

## Histórico
Em 2018 eu desenvolvi esse tema usando o padrão e boas práticas para construção de temas WordPress/WooCommerce. Já em 2019, outros programadores atuaram desenvolvendo outras funcionalidade e outras correções, mas acabaram inserindo códigos e plugins de maneira incorreta ou fora dos padrões. Isso provocou alguns problemas técnicos e código sujo. Ao fazer qualquer alteração, deve-se atentar a esses problemas e na medida do possível corrigi-los. Em 2020 reassumi por alguns meses o desenvolvimento, e alguns pontos já foram melhorados, mas outros precisam de atenção, em especial cabeçalho e rodapé, e alguns templates estáticos que ainda apresentam bastante problemas. Esses problemas e falta de padrões, por hora não afetam as funcionalidades e segurança da aplicação, mas é necessário a correção para evitar problemas futuros e para buscarmos uma excelência no produto em questão: a Loja Virtual BeWatch.
O tema depende de alguns plugins para funcionar, mas existem outros ativados que cumprem propósito de marketing, SEO, Frete e outras funcionalidades administrativas. Os essências para a parte técnica são:
<li>Advanced Custom Fields</li>
<li>Advanced Custom Fields: Categories</li>
<li>Advanced Custom Fields: Repeater Field</li>
<li>Brazilian Market on Loja Be!</li>
<li>Claudio Sanches - Correios for Loja Be!</li>
<li>Claudio Sanches - PagSeguro for Loja Be!</li>
<li>Editor clássico</li>
<li>WooCommerce</li>
<li>Melhor Envio v2</li>
<li>Nextend Social Login</li>
<li>WP Mail SMTP</li>

Todos os demais plugins instalados são opcionais

## Descrição dos diretórios e arquivos importantes:

<li><b>assets:</b> pasta criada por outro programador, contêm arquivos de plugins como slides e outros scripts, não é claro quais exatamente são ou não usados.</li>
<li><b>core:</b> pasta com os arquivos originais do Bootstrap3 que é usado no tema, apenas para referência, não é usado no código fonte do tema</li>

<li><b>css:</b> pasta com todos os arquivos principais de estilo CSS
	<ul style="padding-left:30px">
		<li>animate.css: animações CSS</li>
		<li>bootstrap-dropdownhover.css: menu dropdown (o menu foi removido por outro programador)</li>
		<li>bootstrap-glyphicons.css: ícones do bootstrap (provavelmente alterado para FontAwesome)</li>
		<li>bootstrap-theme.css: arquivo padrão estilos Bootstrap</li>
		<li>bootstrap-theme.min.css: arquivo padrão estilos Bootstrap</li>
		<li>bootstrap.css: arquivo padrão estilos Bootstrap</li>
		<li>bootstrap.min.css: arquivo padrão estilos Bootstrap</li>
		<li>font.css: fontes customizadas do site</li>
		<li>large.css: CSS para telas grandes (não utilizado)</li>
		<li>lightslider.css: adicionado por outro programador, não sei o que faz ou se é usado</li>
		<li>phone.css: CSS para telas pequenas (não utilizado)</li>
		<li>style.css: arquivo principal de estilos CSS do site</li>
		<li>sweetalert2.min.css: plugin de confirmações e retornos de erros para o usuário</li>
		<li>tablet.css: CSS para telas médias (não utilizado)</li>
	</ul>
</li>


<li><b>imagens:</b> pasta criada por outro programador, contêm imagens SVG</li>
<li><b>images: pasta padrão para arquivos de imagens do tema</b></li>
<li><b>js</b>: pasta padrão para os scripts JS do site
		<ul>
		<li>bootstrap-dropdownhover.js: arquivo padrão Bootstrap</li>
		<li>bootstrap-notify.js: notificações para o usuário</li>
		<li>bootstrap.js:  arquivo padrão Bootstrap</li>
		<li>bootstrap.min.js:  arquivo padrão Bootstrap</li>
		<li>carrinho.js: arquivo para lógicas de processamento do carrinho</li>
		<li>cidades-estados-v0.2.js: arquivo para carregamento automático de cidades e estados para formulários</li>
		<li>dist: diretório com arquivos dos plugins para máscara de formulários</li>
		<li>html2canvas.js: arquivo com scripts para prints de uma determinada DIV, usada para prints de personalização de produtos</li>
		<li>jquery-2.1.4.js: jquery usado no tema</li>
		<li>scripts-beblack.js: scripts para manipulação das lógicas para o tipo de produto BEBLACK</li>
		<li>scripts-digital.js: scripts para manipulação das lógicas para o tipo de produto DIGITAL</li>
		<li>scripts-gift-cards-offline.js: scripts para manipulação das lógicas para o tipo de produto GIFT CARDS OFFLINE</li>
		<li>scripts-gift-cards-online.js:  scripts para manipulação das lógicas para o tipo de produto GIFT CARDS ONLINE</li>
		<li>scripts-pulseiras.js: scripts para manipulação das lógicas para o tipo de produto PULSEIRAS</li>
		<li>scripts-rings.js:  scripts para manipulação das lógicas para o tipo de produto ANÉIS</li>
		<li>scripts-silicone.js:  scripts para manipulação das lógicas para o tipo de produto SILICONE</li>
		<li>scripts.js:  scripts para manipulação das lógicas para o tipo de produto METAL E OUTROS SCRIPTS GERAIS</li>
		<li>style.js: criado por outro programador, não sei o propósito</li>
		<li>sweetalert2.min.js: alertas e avisos para o usuário</li>
		<li>wow.min.js: animações do site</li>
		</ul>
</li>
<li><b>modelo-produtos:</b> modelos de tipo de produtos
   <ul>
        <li>antigo modelo digital.php: Backup de um modelo antigo</li>
	<li>backup pulseira couro.php: Backup de um modelo antigo</li>
	<li>beblack.php: modelo de produto categoria BEBLACK</li>
	<li>benight.php: modelo de produto categoria BENIGHT</li>
	<li>digital.php: modelo de produto categoria DIGITAL</li>
	<li>gift-cards-offline.php: modelo de produto GIFT CARDS OFFLINE</li>
	<li>gift-cards-online.php: modelo de produto GIFT CARDS ONLINE</li>
	<li>metal.php: modelo de produto categoria METAL</li>
	<li>produtos-simples.php: modelo de produto QUALQUER OUTRO PRODUTO SIMPLES</li>
	<li>pulseiras.php: modelo de produto PULSEIRAS</li>
	<li>rings.php: modelo de produto RINGS</li>
	<li>silicone.php: modelo de produto SILICONE</li>
   </ul>

</li>
<li><b>otimizacao2020:</b> Novos arquivos JS criados em 2020 para deixar a administração das pulseiras dos relógios e marcadores de hora dos relógios, de forma dinâmica:
	<ul>
		<li>benight.php: scripts JS pulseiras/marcadores dinâmicos para categoria BENIGHT </li>
		<li>loop.php: scripts JS pulseiras/marcadores dinâmicos para categoria DIGITAL/LOOP </li>
		<li>metal.php: scripts JS pulseiras/marcadores dinâmicos para categoria METAL/STEEL </li>
		<li>silicone.php: scripts JS pulseiras/marcadores dinâmicos para categoria SILICONE/SPLASH </li>
	</ul>
</li>
<li><b>phpmailer:</b> arquivos gerais de envio de e-mails (SMTP)</li>
<li><b>woocommerce:</b> arquivos gerais padrão WooCommerce </li>

<li>404.php: arquivo padrão para páginas não encontradas</li>
<li>PURPLE.png: criado por outro programador, não sei por que fora da pasta padrão</li>
<li>apagar-wishlist.php: apagar produto da lista de desejos</li>
<li>banner_mobile_black.php: criado por outro programador, não sei o propósito</li>
<li>be.svg: logo da BE em SVG (deveria estar na pasta padrão de imagens)</li>
<li>be2.svg: logo da BE em SVG (deveria estar na pasta padrão de imagens)</li>
<li>be3.svg: logo da BE em SVG (deveria estar na pasta padrão de imagens)</li>
<li>carrinho-2019.php: criado por outro programador, não sei o propósito, apresenta problemas</li>
<li>cartao-presente.php: criado por outro programador, para cartão presente, apresenta problemas</li>
<li>categoria_be_splash_nova.php: criado por outro programador, para categorias avulsas, apresenta problemas</li>
<li>categoria_be_steel_nova.php: criado por outro programador, para categorias avulsas, apresenta problemas</li>
<li>categoria_loop_nova.php: criado por outro programador, para categorias avulsas, apresenta problemas</li>
<li>cola-produto.htp: criado por outro programador, aparentemente uma copia de template</li>
<li>debug.log: arquivo de log de erros do servidor</li>
<li>enviar-revenda-2020.php: disparo de e-mail com dados do formulário de revenda (versão 2020)</li>
<li>enviar-revenda.php: disparo de e-mail com dados do formulário de revenda (versão 2019)</li>
<li>enviarmsg.php: disparo de e-mail do formulário de contato</li>
<li>error_log: arquivo de log de erros do WordPress</li>
<li>footer-comum.php: criado por outro programador, provavelmente parte do rodapé, apresenta problemas</li>
<li>footer-novo.php: criado por outro programador, provavelmente parte do rodapé, apresenta problemas</li>
<li>footer.php: arquivo padrão do rodapé do site</li>
<li>functions.php: arquivo de funções padrão do tema</li>
<li>header.php: arquivo do cabeçalho do tema</li>
<li>home3.php: versão da homepage criada por outro programador (DESATIVADO)</li>
<li>home4.php: versão da homepage criada por outro programador (DESATIVADO)</li>
<li>homepage-nova-novembro.php: versão da homepage criada por outro programador (DESATIVADO)</li>
<li>homepage.php: versão  original da homepage 2018 (DESATIVADO)</li>
<li>homepage2019.php: versão 2019 da homepage (DESATIVADO)</li>
<li>homepage2020.php: versão 2020 da homepage</li>
<li>index.php: arquivo inicial do tema</li>
<li>login-false.php: criado por outro programador, não sei o que faz</li>
<li>metal.php: criado por outro programador, não sei o que faz, nem o propósito de estar fora da pasta padrão</li>
<li>minha-conta.php: template padrão da página Minha Conta</li>
<li>mobile.php: template parte das sessões exclusicas Mobile (apresenta problema, outro programador instalou plugin de terceiros para mobile)</li>
<li>modelo-carrinho.php: template padrão para o carrinho</li>
<li>modelo-categoria-1.php: template para exibição de categorias</li>
<li>modelo-categoria-2.php: template para exbição de categorias</li>
<li>modelo-categoria-3.php: template para exibição de categorias</li>
<li>modelo-revendedor.php: template página de revendedores</li>
<li>onde-encontrar.php: template página onde encontrar</li>
<li>page-modelo-2.php: template para páginas</li>
<li>page.php: template padrão para páginas</li>
<li>perfil-artista.php: template para a página de perfil do artista</li>
<li>perguntas-frequentes.php: template para a página de FAQ</li>
<li>pixel-facebook.php: template part para códigos PIXEL FACEBOOK</li>
<li>preload.php: template part para GIF de carregamento</li>
<li>proc-cep.php: template part para carregar dados do simulador de FRETE (aparentemente desativado por outro programador)</li>
<li>processa.php: criado por outro programador, não sei o que faz</li>
<li>processamento-ajax.php: processamento AJAX do carrinho</li>
<li>rastreio.php: template part para busca/consulta de código de rastreio</li>
<li>revenda-formulario.php: template para envio de mensagens dados formulário de revenda</li>
<li>revenda2020.php: template para página de SEJA UM REVENDEDOR</li>
<li>salvar-wishlist.php: salvar arquivo na lista de desejos</li>
<li>screenshot.jpg: capa do tema</li>
<li>script-db.php: scripts para corrigir problema de estoque em produtos novos da loja</li>
<li>search.php: template para exibir resultado de pesquisa</li>
<li>single.php: arquivo padrão para exibição de SINGLE POST TYPE</li>
<li>slider_produto_desktop.php: criado por outro programador não sei o que faz</li>
<li>slider_produto_new_arrivals.php: criado por outro programador não sei o que faz</li>
<li>slider_produto_quem_viu.php: criado por outro programador não sei o que faz</li>
<li>slideshow-2.php: template parte para slides rotativos do site</li>
<li>slideshow.php: template parte para slides rotativos do site
<li>style.css: nome e informações do tema</li>
<li>suporte.php: template da página de suporte</li>
<li>teste-facebook.php: criada por outro programador não sei o que faz</li>
<li>validar-usuario-facebook.php: criada por outro programador não sei o que faz</li>
<li>woo-artistas.php: página para listagem dos artistas</li>
<li>woo-carrinho-antiga.php: template antigo da página de carrinho</li>
<li>woo-carrinho.php: template da página de carrinho</li>
<li>woo-categoria-filha.php: template para exibir categorias filhas de uma categoria</li>
<li>woo-categoria-pai.php: template para exibir apenas categorias pais</li>
<li>woo-categorias.php: template padrão de categorias WooCommerce</li>
<li>woo-contatos.php: template part para edição de dados de contato MINHA CONTA</li>
<li>woo-enderecos.php: template par para edição de dados de endereços MINHA CONTA</li>
<li>woo-lista-de-desejos.php: template para exibir produtos da lista de desejos MINHA CONTA</li>
<li>woo-login-cadastro.php: template do formulário de login ou cadastro MINHA CONTA</li>
<li>woo-pagina-abstrata.php: template página padrão WooCommerce</li>
<li>woo-pagina.php: template página pdrão WooCommerce</li>
<li>woo-pedidos.php: template página WooCommerce MEUS PEDIDOS - MINHA CONTA</li>
<li>woo-single-produto.php: template WooCommerce para exibir um produto</li>
<li>woocommerce.php: template padrão de integração WooCommerce</li>

## Lógica básica de exibição dos produtos BeWatch

A exibição básica de um relógio BeWatch:

![Documentação técnica BeWatch - 2018/2020](https://www.diogenesjunior.com.br/docs/logica-produtos-0.jpg)

As layers que compôem o produto são divididas da sequinte maneira:

![Documentação técnica BeWatch - 2018/2020](https://www.diogenesjunior.com.br/docs/logica-produtos.jpg)

Onde dependendo da escolha do usuário nas pulseiras, marcadores, ícones ou escrita, vamos alterar o SRC das tags IMGS correspondêntes a cada layer. No caso da escrita, a lógica é semelhante, mas o texto personalizado do usuário, é inserido em uma div simples:

![Documentação técnica BeWatch - 2018/2020](https://www.diogenesjunior.com.br/docs/logica-produtos2.jpg)

![Documentação técnica BeWatch - 2018/2020](https://www.diogenesjunior.com.br/docs/logica-produtos3.jpg)



## Lógica de inclusão de produto no carrinho

Cada produto adicionado ao carrinho, terá diferentes opções personalizadas pelo usuário. Para isso, adicionamos CUSTOM METAS a cada produto, dentro de cada pedido WooCommerce. Além disso, tiramos um "print" da DIV das layers de personalização, para que o pessoal da administração da BeWatch, veja da mesma forma que o usuário, como ficou o resultado final da personalização. Esse print é feito através da biblioteca <b>html2canvas.js</b> que tira um print de da DIV, transformando esse print em binário, e ai salvamos esse binário em uma imagem dentro do servidor. O fluxo de inclusão do produto no carrinho, segue o seguinte diagrama:

![Documentação técnica BeWatch - 2018/2020](https://www.diogenesjunior.com.br/docs/logica-produtos4.jpg)

<p>
Para adicionar o CUSTOM META ao produto do carrinho WooCoommerce, temos um filtro que é acionado quando enviamos a chave via POST, como pode ser visto abaixo, usando como exemplo PULSEIRA
</p>

https://gist.github.com/diogenesjup/2609465edcac14319153f2d55e1b6da2

<p>
Para o print da imagem a lógica é parecida, mas precisamos salvar o código binário da imagem (BASE64) em uma imagem real dentro do servidor, isso é feito através do código:
</p>

https://gist.github.com/diogenesjup/74594a25bd9b97ed6a1dfd85a1348fae

<p>
As CUSTOM METAS ficam salvas no wp-admin, em cada detalhe do pedido:
</p>

![Documentação técnica BeWatch - 2018/2020](https://www.diogenesjunior.com.br/docs/logica-produtos5.jpg)

## Conclusão e observações finais
- Qualquer dúvida técnica pode ser enviada para contato@diogenesjunior.com.br<br>
- Atualizar o WordPress ou o WooCommerce para a versão mais recente é totalmente seguro e recomendado.A única ressalva aqui é referente os plugins que não estão listados nesse documento, por que não sei como será o comportamento dele.
- O bug do estoque para novos produtos (relatados na descrição do arquivo script-db.php) se da por causa que ao adicionar um novo produto, por alguma razão, ele já começa com o status do estoque OUT OF STOCK, mesmo se duplicando de um produto com estoque. Para corrigir isso, o script em questão da um UPDATE em todo o banco, deixando todos eles em estoque (a administração da BeWatch não utiliza estoque único por produto):<br><br>
<i>
meta_key = '_stock'<br>
meta_value = '100'<br><br>
meta_key = '_stock_status'<br>
meta_value = 'instock'<br>
</i><br><br>

- Ao fazer atualizações no código fonte, cuidado com o cache, o plugin escolhido e utilizado pela admnistração BeWatch costuma demorar para propagar alterações nos arquivos PHP, CSS e JS.
