# Curso da Alura  <https://www.alura.com.br/>

<h1> 1 - O que é o Angular?</h1>

O Angular é uma plataforma para construir aplicações Web, mobile ou desktop, que oferece um framework para desenvolver usando TypeScript, HTML e CSS. Ele é um dos frameworks mais populares do mercado de desenvolvimento front-end

O Angular é usado para criar páginas web SPA (Single Page Application) baseadas em componentes, o que facilita a manutenção de layouts complexos e isola as responsabilidades de cada parte do seu código

<h1> 2 - Entendendo o TypeScript </h1>

É o superset do JavaScript, nele você pode adicionar tipagens as suas variáveis. É muito usado em conjunto com os frameworks web, Angular, Vue, React, entre outros.

Esse sistema de tipos é uma das features mais famosas da linguagem, mas ela não é a única. Utilizando de análise estática de código e de um compilador que transforma seu código em JavaScript, ele pode te dar sugestões de como melhorar seu código e evitar erros enquanto gera uma documentação simples do código criado. 

Com tudo isso, ele é conhecido por trazer uma experiência muito agradável para quem está programando o projeto.

<h1> 3 - Comandos Úteis </h1>

✔️ npm install -g @angular/cli: Instala o angular CLI de forma global na sua máquina. </br>
✔️ ng new projectName: Cria um novo projeto angular </br>
✔️ ng --version: Verifica a versão do seu angular </br>
✔️ ng serve --open: Executa projeto angular abrindo automaticamente o browser </br>

<h1> 4 - Entendendo um pouco da estrutura </h1>

Em Angular, tudo é um componente, capaz de guardar um comportamento, o CSS, e a marcação HTML, a estrutura, em um único local. Assim, a página localhost:4200 não é diferente no Angular, já que uma página também é um componente, e possui HTML, CSS e, caso haja, JavaScript, tudo vinculado em um único objeto denominado componente. Assim, <app-root> indica a existência de componentes.

Dentro do .ts do seu componente você verá um decorator demarcado com o @Componente, nele está incluído uma metainformação sobre seu componente, e um componente só existe por causa dessa anotação.

<img src="https://lh3.googleusercontent.com/0ins24pKrWhcubhwzSNm-Iy-jQuyF3X4lEU9fy66ybjnYfQdQjVJyQSfFzMVvyD8hnAkZv2S8dWc0uTsVYhnIZbK8cs-dSRz8Vjd62R9OUpy2dwsXjR9weMfAyiBNW8FKFEpI1Mm" alt="Estrutura angular">


<h2> 4.1 - O que é uma metainformação? </h2>

Ao criarmos instâncias desta classe, criamos objetos. Estamos incluindo mais uma informação desta classe, que diz respeito ao framework. Então, a classe AppComponent só é um componente porque está anotada com @Component. Nele, existe um selector: 'app-root', mesmo nome encontrado em index.html

Esse seletor nos permite utilizar os componentes de forma declarativa, então dentro do .ts do app componente temos, por exemplo:

1. selector: ‘app-root’: Diz respeito ao nome do componente que será utilizado em suas instâncias.
2. templateUrl: ‘./app.component.html’: Diz respeito a localidade do html deste componente.
3. styleUrls: [‘./app.component.css’]: Diz respeito a localidade do css deste componente.

Quando uma aplicação Angular é carregada pela primeira vez, sabemos que é a <app-root> que será carregada, pois, ela, na sua forma declarativa no selector, é que está no index.html.

<h1>5 - Data Binding</h1>
É o processo de você pôr no html valores que estão no ts do seu componente.

<img src="https://lh5.googleusercontent.com/p_4h9IW3IKzK2k7Ftbyv3Tvq8Yr3BpfdzmwtwNtnPQ-Euhv8r8XfxKxefHpi3U-p7El1-YsYJxU_Q4YN__WzEB2laLWUcNl4yC7vGGvhUy396NzpmS8QrVLYB8SPln9kRBAP9Sgv" alt="Data Binding angular">

<img src="https://lh5.googleusercontent.com/bwzvDhOp_cY_7EDiM7LI2_KB28a345GfhCc3LVHp00AbbqZoNs7OnXkzrSNCd8oaHo3Gz9Rr8ISNFU4SuQj45vdXEUrXJ7HSduRJqXrz7ksceFGuZPXswaYXZ4Ywv6zKDHgVltcA" alt="Data Binding 2 angular">

O Data binding implica em uma associação de dados com uma fonte de dados que, no nosso caso, está no componente, com seu template (nomenclatura do Angular), ou view. Nele, quando encontramos esta sintaxe chamada de Angular expression (AE) {{ }}, e quando o Angular for renderizar este template do componente, ele se deparará com uma lacuna, que neste caso está apontando para a propriedade title.
