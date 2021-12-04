# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Para alcançar os objetivos propostos, fizemos perguntas a pessoas (escolhidas de forma aleatória) que correspondem às características citadas no tópico "público-alvo" do projeto. Nessa pesquisa, a coleta de dados foi baseada em cinco questões, suficientes para atingir os objetivos propostos pelo projeto.

## Personas

Felipe Colorado tem 29 anos, formação em design de moda, é digital influencer e fã de tecnologias e de produtos inovadores. Possui um grande canal de moda no Youtube, no qual apresenta dicas de moda e indicações de compras para seus inscritos. Tem como hobbies ir na academia e jogar video game e poker. Costuma utilizar os aplicativos Instagram e Youtube. Como é um grande consumidor de produtos online, principalmente de vestuários, tem uma enorme frustação quanto a quantidade de produtos comprados com o tamanho errado. <br>
Luana Martins tem 26 anos, é proprietária de uma  loja digital e é criadora de conteúdo. Sua principal ferramenta de trabalho é o Instagram. Tem como hobbies malhar na academia e fazer dança. Costuma utilizar o aplicativo Instagram. Luana tem um grande problema quanto a compra errada no tamanho das peças (por parte dos clientes), gerando a insatisfação do cliente, que não volta a comprar e, também, o prejuízo financeiro perante os fretes. <br>
Patricia Zamboni tem 34 anos e é engenheira civil de uma grande empresa. Tem como hobbies ler livros e ir a bares com os amigos. Costuma utilizar os aplicativos Instagram, LinkedIn, Facebook e Twitter. Ela costuma fazer compras online. Grande parte do que compra é via Amazon, como o tapete higiênico de seus cachorros, os livros que lê e utensílios para casa. De vez em quando, compra calçados e acessórios, mas nunca teve coragem de comprar roupas, pois já escutou muita opinião negativa a respeito, vindo de sua irmã e de alguns amigos.

## Histórias de Usuários

Com base na análise das personas, foram identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`  |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------ |----------------------------------------|
|Felipe Colorado     | "Experimentar" roupas de forma virtual| Para ter certeza de que escolhi a peça certa para mim.|
|Felipe Colorado     | Comprar roupas de forma online      | Porque nem sempre encontro o que desejo nas lojas físicas.|
|Felipe Colorado     | Comprar roupas de forma virtual     | Para me manter sempre em dia com a moda, o que é importante para o meu canal.|
|Luana Martins       | Proporcionar o “provador virtual” aos meus clientes| Porque desejo aumentar o faturamento do meu negócio.|
|Luana Martins       |	Poder "experimentar" roupa de forma virtual	| Para abastecer minha loja de acordo com o gosto dos meus clientes.|
|Patrícia Zamboni    |	Poder "experimentar" roupa de forma virtual	| Para ser mais assertiva na minha escolha.|
|Patrícia Zamboni    |	Poder "experimentar" roupa de forma virtual	| Porque nem sempre me sinto à vontade na loja física.|

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID   | Descrição do Requisito  | Prioridade |
|-----|-----------------------------------------|----|
|RF-01|	O site deve apresentar na página principal a descrição do serviço e como ele pode ajudar o usuário | ALTA | 
|RF-02| O site deve apresentar um menu simples, intendível e interativo.	| ALTA |
|RF-03| O site deve apresentar de forma explícita o local de cadastro do usuário simplificado (via facebook e google ou cadastro padrão)	| MÉDIA |
|RF-04| O site deve oferecer um redirecionamento que permita ao usuário ter acesso aos produtos dos parceiros.	| MÉDIA |
|RF-05| O site deve permitir visualizar as informações de contatos do vendedor do produto. |	MÉDIA |
|RF-06| O site deve permitir salvar vestimentas preferidas |	BAIXA |
|RF-07| O site deve permitir verificar as vestimentas salvas como preferidas	| BAIXA |
|RF-08| O site deve permitir que usuários possam comentar nos produtos dando feedback sobre os mesmos	| BAIXA |
|RF-09| O site deve exibir os comentários registrados juntamente com o produto exibido	| BAIXA |


### Requisitos não Funcionais

|ID    | Descrição do Requisito  |Prioridade |
|------|-------------------------|----|
|RNF-01|	O site deve ser publicado em um ambiente acessível publicamente na Internet (Repl.it, GitHub Pages, Heroku) |	ALTA |
|RNF-02| O site deverá ser responsivo permitindo a visualização em um celular de forma adequada	| ALTA |
|RNF-03| O site deve ter bom nível de contraste entre os elementos da tela em conformidade |	MÉDIA |
|RNF-04|	O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge)	| ALTA |
|RNF-05| O site deve permitir que o cadastro de usuário seja feito em até 20 segundos	| ALTA |
|RNF-06|	O site deve funcionar 24 horas por dia 7 dias por semana	| ALTA |
|RNF-07|	O site deve funcionar normalmente mesmo tendo 10.000 usuários utlizando simultâneamente	| ALTA |
|RNF-08|	O site deve ser suportado em todos os navegadores e sistemas operacionais |	ALTA |
|RNF-09|	O sistema deve ser capaz de atender 50 requisições por segundoe ignorar requisições acima de 100a para não desgastar o tempo de resposta	| ALTA |

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|RE-01|	A norma ISO 9126 deve ser usada para avaliar a qualidade do site.|
|RE-02|	O site deve ser desenvolvido às tecnologias básicas da Web no Front-end|
|RE-03|	A equipe não pode subcontratar o desenvolvimento do trabalho.|
|RE-04|	O site deve estar acessível na Web.|
