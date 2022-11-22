<h1>Explorando Padrões de Projetos na Prática com Java</h1>

<p>Repositório com as implementações dos padrões de projeto explorados no Lab "Explorando Padrões de Projetos na Prática com Java", disponibilizado pela plataforma DIO Innovation. Especificamente, este projeto explorou alguns padrões usando o Spring Framework, são eles:

<p> -> Singleton: @Bean e @Autowired<br>
<p> -> Strategy/Repository: @Service e @Repository<br>
<p> -> Facade: Foi construído uma API REST com o mesmo objetivo desse padrão, abstrair a complexidade das seguintes integrações: Spring Data JPA e ViaCEP(Feign).<br>

Utilizou-se também o banco H2.

O desafio do curso era reproduzir o projeto que foi criado durante as aulas. Com a utilização do Spring foi possível observar como ele abstrai uma série desses
padrões de projeto.

<h2>
🛑 Padrões de Projeto
</h2>

<p>Padrões de Projeto são soluções consolidadas para problemas recorrentes no desenvolvimento e manutenção de software orientado a objetos.

São comumente classificados nas seguintes categorias:

🔸 <strong>Padrões Criacionais:</strong> Fornecem vários mecanismos de criação de objetos, que aumentam a flexibilidade e reutilização de código já existente.

  <strong>-> Abstract Factory:</strong> Permite que você produza famílias de objetos relacionados sem ter que especificar suas classes concretas;<br> 
	<strong>-> Builder:</strong> Permite construir objetos complexos passo a passo. O padrão permite produzir diferentes tipos e representações de um objeto usando o mesmo código de construção;<br>
	<strong>-> Factory Method:</strong> Fornece uma interface para criar objetos em uma superclasse, mas permite que as subclasses alterem o tipo de objetos que serão criadows;<br>
	<strong>-> Prototype:</strong> Permite que você copie objetos existentes sem fazer seu código dependente de suas classes;<br> 
	<strong>-> Singleton:</strong> Permite a você garantir que uma classe tem apenas uma instância, enquanto provê um ponto de acesso global para esta instância.<br>

🔸 <strong> Padrões Comportamentais:</strong> São voltados aos algoritmos e a designação de responsabilidades entre objetos.
<p>
 	<strong>-> Chain of Responsibility:</strong> Permite que você passe pedidos por uma corrente de handlers. Ao receber um pedido, cada handler decide se processa o pedido ou passa para o próximo handler da corrente;<br> 
	<strong>-> Command:</strong> Transforma o pedido em um objeto independente que contém todas a informação sobre o pedido. Essa transformação permite que você parametrize métodos com diferentes pedidos, atrae ou coloque a execução do pedido em uma fila, e  suporte operações que não podem ser feitas;<br>
	<strong>-> Iterator:</strong> Permite que você percorra elementos de uma coleção sem expor as representações estruturais deles (lista, pilha, árvore, etc);<br>
	<strong>-> Mediator:</strong> Permite que você reduza as dependências caóticas entre objetos. O padrão restringe comunicações diretas entre objetos e os força a colaborar apenas através do objeto mediador;<br>
	<strong>-> Memento:</strong> Permite que você salve e restaure o estado anterior de um objeto  sem revelar os detalhes de sua implementação;<br>
	<strong>-> Observer:</strong> Permite que você defina um mecanismo de assinatura para notificar múltiplos objetos sobre quaisquer eventos que aconteçam com o objeto que eles estão observando;<br>
	<strong>-> State:</strong> Permite que um objeto altere seu comportamento quando seu estado interno muda. Parece como se o objeto mudasse de classe;<br>
	<strong>-> Strategy:</strong> Permite que você defina uma família de algoritmos, coloque-os em classes separadas, e faça os objetos deles intercambiáveis;<br>
	<strong>-> Template Method:</strong> Define o esqueleto de um algoritmona superclasse mas deixa as subclasses sobrescreverem etapas específicas do algoritmosem modificar sua estrutura.<br>
	<strong>-> Visitor:</strong> Permite que você separe algoritmos dos objetos nos quais eles operam;<br>

🔸 <strong> Padrões Estruturais:</strong> Explicam como montar objetos e classes em estruturas maiores mas ainda mantendo essas estruturas flexíveis e eficientes.
<p>
	<strong>-> Adapter:</strong> Permite a colaboração de objetos de interfaces incompatíveis;<br>
	<strong>-> Bridge:</strong> Permite que você divida uma classe grande ou um conjunto de classes intimamente ligadas em duas hierarquias separadas - abstração e implementação - que podem ser desenvolvidas independentemente umas das outras;<br>
	<strong>-> Composite:</strong> Permite que você componha objetos em estrutura de árvores e então trabalhe com essas estruturascomo se fossem objetos individuais;<br>
	<strong>-> Decorator:</strong> Permite que você adicione novos comportamentos a objetos colocando eles dentro de um envoltório (wrapper) de objetos que contém os comportamentos;<br>
	<strong>-> Facade:</strong> Fornece uma interface simplificada para uma biblioteca, um framework, ou qualquer outro conjunto complexo de classes;<br> 
	<strong>-> Flyweight:</strong> Permite que você coloque mais objetos na quantidade disponível de RAM ao compartilhar partes do estado entre múltiplos objetos ao invés de manter todos os dados em cada objeto;<br>
	<strong-> roxy:</strong> Permite que você forneça um substituto ou um espaço reservado para outro objeto. Um proxy controla o acesso ao objeto original, permitindo que você faça algo ou antes ou depois do pedido chegar ao objeto original.<br>


Referência:
https://refactoring.guru/pt-br/design-patterns
