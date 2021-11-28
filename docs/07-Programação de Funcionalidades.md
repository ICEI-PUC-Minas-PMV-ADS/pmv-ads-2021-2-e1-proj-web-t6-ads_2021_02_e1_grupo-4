# Programação de Funcionalidades

Nesta seção são apresentadas as telas desenvolvidas para cada uma das funcionalidades do sistema. O respectivo endereço (URL) e outras orientações de acesso são apresentadas na sequência.


## Home

A tela referente ao "Home" explica ao usuário como utilizar os serviços da "Size", utilizando texto e um vídeo educativo.  

### Requisitos Atendidos

- RF-01
- RF-02

### Artefatos de Funcionalidade

- index.html
- style.css
- style-home.css
- videosize.mp4

### Estrutura de dados

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width">
	<title></title>

	<link rel="stylesheet" href="reset.css">
	<link rel="stylesheet" href="style.css">
	<link href="https://fonts.googleapis.com/css?family=Montserrat&display=swap" rel="stylesheet">
</head>

<body>
	<header>
		<div class="caixa">
			<h1><img src="logo.png"></h1>
			<nav>
				<ul>
					<li><a href="index.html">Home</a></li>
					<li><a href="sobre.html">Sobre Nós</a></li>
					<li><a href="login.html">Login</a></li>
					<li><a href="downloadapp.html">Download App</a></li>
				</ul>
			</nav>
		</div>
	</header>

	<main>
		<div align="center" class="textoprincipal">
			<p>Size ajuda seu cliente a encontrar o tamanho perfeito em poucos cliques e personaliza a experiência de compra com base nas medidas encontradas,<br>

			 recomendando produtos que vão fazer você vestir melhor.</p><br>

			<p>Um provador virtual que respeita a individualidade!</p><br>



		<div align="center" class="funcapp">
			<img src="funcaodoapp.jpg">
			<p>Nossas recomendações são transparentes: exibimos as medidas do corpo e permitimos que sejam ajustadas.<br>
			 Consideramos como irá vestir em cada tipo de medida e em todos os tamanhos disponíveis. Não somos comparadores de marcas e nem estatísticos.
			</p>
			</p>Reconhecemos as medidas corporais de cada indivíduo e as comparamos com medidas específicas de cada cada produto têxtil,<br>
			 calçado e acessório. Entregamos a melhor recomendação de tamanho: a que respeita as medidas de cada pessoa e como ela deseja se expressar (caimento justo, na medida, ou mais folgado).
			<br> Ou seja, entregamos efetivamente a personalização na escolha do tamanho.</p>
			<br><br>
		</div>
		<section class="video">
			<div align="center">
				<video width="900" height="543" controls autoplay>
				<source src="videosize.mp4" type="video/mp4">
				<source src="movie.ogg" type="video/ogg">

			</div>
		</section>

		<section class="mapa">
			<h3 class="titulo-principal">Localização</h3>
			<div class="mapa-conteudo">
				<iframe
					src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3704.508992102077!2d-46.60071468505418!3d-21.799256385586155!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94c9db66b5f8901b%3A0xc4bccba21b48f3bc!2sPUC%20Minas%20Po%C3%A7os%20de%20Caldas!5e0!3m2!1spt-BR!2sbr!4v1637371518168!5m2!1spt-BR!2sbr"
					width="1000" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
			</div>
		</section>
			<div>

			</div>
		</section>
	</main>
	<footer>
		<p>© Copyright Size Clothing S/A<br></p>
		<p>CNPJ 15.095.271/0005-79 Av. Padre Cletus Francis Cox, 1661 - Country Club, Poços de Caldas - MG, 37714-620</p>
		<p>Telefone: (44) 3351-5000<br>Todos os direitos reservados.</p><br>
	</footer>
</body>
</html>

### Instruções de Acesso

1.	Abra um navegador de Internet e informe a seguinte URL: https://rodrigomendesdev13.github.io/size/index.html
2.	A tela "Home" será exibida e o usuário poderá navegar pelas informações apresentadas.

## Login

A tela referente ao "Login" permite ao usuário se cadastrar para iniciar suas compras no site.

### Requisito Atendido

- RF-03

### Artefatos da Funcionalidade

- login.html
- login.css

### Estrutura de Dados

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://kit.fontawesome.com/1ab94d0eba.js" crossorigin="anonymous"></script>
    <title>Login</title>
    <link rel="stylesheet" href="login.css">

</head>
<body>
    <main class="container">
        <h2>Já possui uma conta?</h2>
        <h3>Informe os dados abaixo para acessá-la.</h3>
        <form action="">
            <div class="input-field">
                <input type="text" name="username" id="username"
                    placeholder="Digite sua senha">
                <div class="underline"></div>
            </div>
            <div class="input-field">
                <input type="password" name="password" id="password"
                    placeholder="Digite sua senha">
                <div class="underline"></div>
            </div>

            <input type="submit" value="Entrar">
        </form>

        <div class="footer">
            <span><a href="cadastro.html">Cadastre-se</a></span>
            <span>ou</span>
            <span>Conecte-se com sua mídia social</span>
            <div class="social-fields">
                <div class="social-field twitter">
                    <a href="#">
                        <i class="fab fa-twitter"></i>
                        Entrar com o Twitter
                    </a>
                </div>
                <div class="social-field facebook">
                    <a href="#">
                        <i class="fab fa-facebook-f"></i>
                        Entrar com o Facebook
                    </a>
                </div>
            </div>
        </div>
    </main>
</body>
</html>

### Instruções de Acesso

1.	Abra um navegador de Internet e informe a seguinte URL: https://rodrigomendesdev13.github.io/size/login.html
2.	A tela de contato será exibida e o usuário poderá inserir suas informações para cadastro.

## Sobre nós

A tela referente à "Sobre Nós" explora o propósito do serviço.

### Requisito Atendido
- RF-02
- RF-05

### Artefatos da Funcionalidade
- sobre.html
- sobre.css

### Estrutura de Dados

<!DOCTYPE html>
<html lang="pt-br">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width">
	<title></title>

	<link rel="stylesheet" href="reset.css">
	<link rel="stylesheet" href="sobre.css">
	<link href="https://fonts.googleapis.com/css?family=Montserrat&display=swap" rel="stylesheet">
</head>

<body>
	<header>
		<div class="caixa">
			<h1><img src="logo.png"></h1>
			<nav>
				<ul>
					<li><a href="index.html">Home</a></li>
					<li><a href="sobre.html">Sobre Nós</a></li>
					<li><a href="login.html">Login</a></li>
					<li><a href="Contato.html">Download App</a></li>
				</ul>
			</nav>
		</div>
	</header>

	<main>
		<div class="descricao">
			Sobre nós Nos últimos dois anos, em meio a pandemia de COVID-19, o e-commerce cresceu vertiginosamente. Somente em 2020, o crescimento das vendas via<br> comércio eletrônico foi de 49%, e a tendência é só aumentar. Os principais segmentos responsáveis por esta elevação são o de moda, de alimentos e de serviços.<br>
			Dentro do setor “moda”, o destaque foi a venda de calçados. Existe espaço para a venda on-line de vestuário e acessórios, mas a experiência atual do consumidor cria<br> entraves para isto. Comprar roupas e acessórios pela internet ainda gera muitas insatisfações. Grande parte delas estão relacionadas a falta de melhores<br> informações sobre o produto e a impossibilidade de experimentá-las. Além disto, uma vez que a compra foi efetuada, se for necessário trocar, existe muito desgaste e<br> perda de tempo, o que resulta na péssima experiência do cliente e na desistência, por parte dele, em realizar compras futuras via internet. Além disto, pode gerar um<br> marketing negativo para a marca/loja, o que resultaria na perda de novos clientes. De acordo com consumidores entrevistados, a única informação segura que eles<br> possuem em relação ao produto está na opinião de pessoas que deixam sua avaliação em compras realizadas. Apesar do alto número de reclamações e da queda no<br> índice de satisfação, é possível embasar soluções para a redução de experiências negativas em compras. Os dois lados (vendedor e comprador) só teriam a ganhar. Por<br> um lado, o comprador teria acesso a mais um meio de comprar roupas e acessórios, de forma mais acessível e/ou barata, sem precisar se deslocar para buscar<br> a peça, no conforto de sua casa. Por outro, o vendedor conseguiria planejar melhor seu estoque, produzindo ou comprando de acordo com a necessidade (por ser uma “venda casada”)<br>
			diminuindo a chance de falta de produtos e/ou excesso, melhorando seu lucro.	
			<br>
			<br>
			<img align="center" id="closetimg" src="closet.jpg">
		</div>		
	</main>
	<footer>
		<p>© Copyright Size Clothing S/A<br></p>
		<p>CNPJ 15.095.271/0005-79 Av. Padre Cletus Francis Cox, 1661 - Country Club, Poços de Caldas - MG, 37714-620</p>
		<p>Telefone: (44) 3351-5000<br>Todos os direitos reservados.</p><br>
	</footer>
</body>
</html>

### Instruções de Acesso
1.	Abra um navegador de Internet e informe a seguinte URL: https://rodrigomendesdev13.github.io/size/sobre.html
2.	Aparecerão o texto referente à seção "Sobre Nós".

## Download do app

A tela referente ao "Download do app" faz referência à sequência do serviço que será prestado, com a utilização de um aplicativo, o qual será produzido em próximos passos do projeto.

### Requisito Atendido
- 

### Artefatos da Funcionalidade
- downloadapp.html

### Estrutura de Dados

<!DOCTYPE html>
<html lang="pt-br">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width">
	<title>Size Clothing Download App</title>
	<link rel="stylesheet" href="reset.css">
	<link rel="stylesheet" href="sobre.css">
	<link rel="stylesheet" href="form.css">
	<link href="https://fonts.googleapis.com/css?family=Montserrat&display=swap" rel="stylesheet">
</head>

<body>
	<header>
		<div class="caixa">
			<h1><img src="logo.png"></h1>
			<nav>
				<ul>
					<li><a href="index.html">Home</a></li>
					<li><a href="sobre.html">Sobre Nós</a></li>
					<li><a href="login.html">Login</a></li>
					<li><a href="downloadapp.html">Download App</a></li>
				</ul>
			</nav>
		</div>
	</header>

	<main>
		<div class="descricao">	
			<img align="center" id="faixa" src="../size/_imagens/faixa_contrucao.gif"
			<br><br>
			<span style="font-weight: bold;">DESCULPE O TRANSTORNO !</span>
			<p>Estamos em desenvolvimento do aplicativo.</p>
			<br>
			<img align="center" id="developer" src="../size/_imagens/dev.gif">
			<br><br>
			<p>Caso queira receber atualizações do andamento do desenvolvimento do aplicativo e quando estiver pronto,<br> clique no botão abaixo para se cadastrar e ficar por dentro das novidades</p><br>
			<div id="botao">
				<a href="cadastro.html"><input type="submit" name="botao" value="Cadastre-se" class="botaoCadastrar"></a>
			</div>
	</main>
	<footer>
		<p>© Copyright Size Clothing S/A<br></p>
		<p>CNPJ 15.095.271/0005-79 Av. Padre Cletus Francis Cox, 1661 - Country Club, Poços de Caldas - MG, 37714-620</p>
		<p>Telefone: (44) 3351-5000<br>Todos os direitos reservados.</p><br>
	</footer>
</body>
</html>

### Instruções de Acesso
1.	Abra um navegador de Internet e informe a seguinte URL: https://rodrigomendesdev13.github.io/size/downloadapp.html
2.	Aparecerá um texto informando que o aplicativo está em desenvolvimento.
