🪙 Convert Money
O Convert Money é uma aplicação web responsiva voltada para a conversão de moedas em tempo real. O projeto simula a conversão do Real Brasileiro (R$) para moedas estrangeiras como o Dólar Americano (US$) e o Euro (€), utilizando manipulação dinâmica do DOM e formatação internacionalizada de dados.


Descrição Técnica de Cada Parte do Projeto
O projeto foi estruturado utilizando a separação limpa de responsabilidades nas três camadas fundamentais do Front-end: Interface (HTML), Estilização (CSS) e Comportamento/Lógica (JavaScript).


1. Interface Humana e Semântica (index.html)
A estrutura do documento foi desenvolvida focando em acessibilidade e semântica web:


<!DOCTYPE html> e Meta Tags: Configuração inicial para garantir a renderização correta de caracteres especiais (UTF-8) e responsividade em dispositivos móveis (viewport).



Tags Semânticas (main, section):Isolam o núcleo do conversor em um card centralizado e separam a área de entradas do usuário da área exclusiva de exibição dos resultados.


Elementos de Formulário (select, input, button): Utilizados para capturar as interações do usuário. O input foi configurado estritamente com o tipo number para evitar inserção de textos inválidos.


IDs e Classes Estratégicos: Identificadores precisos (como .convert-button e .currency-select) que servem de ponte para a estilização e para a manipulação via código.


2. Identidade Visual e Layout (assets/estilo.css)
A folha de estilo transforma o esqueleto HTML em um aplicativo moderno e elegante:


Reset Global (*): Aplicação de box-sizing: border-box, zerando margens e preenchimentos padrão para garantir consistência visual entre diferentes navegadores.


Tipografia: Integração com a fonte Roboto via Google Fonts para uma leitura limpa.


Layout com Flexbox: Utilizado na tag body para centralizar perfeitamente o card na tela, e na section de resultados para organizar os dados das moedas verticalmente e alinhar os elementos ao centro.


Microinterações (:hover, :active, transition): Adição de efeitos visuais suaves de opacidade no botão principal, melhorando a experiência do usuário (UX) ao indicar que o elemento é clicável.


3. Inteligência e Dinamismo (assets/script.js)
O script é o motor da aplicação, responsável por processar os dados e atualizar a interface sem a necessidade de recarregar a página (Single Page behavior):


Mapeamento do DOM (document.querySelector): Captura e manipula os elementos do HTML em tempo real.


Tratamento e Validação de Dados: Uso de parseFloat() e checagens com isNaN() para impedir que valores em branco, nulos ou negativos quebrem os cálculos do sistema.


API de Internacionalização (Intl.NumberFormat): O ponto alto da lógica. Garante que os valores monetários sejam exibidos exatamente sob as regras de suas respectivas 
regiões (ex: pt-BR para Real, en-US para Dólar e de-DE para Euro), formatando pontuações e símbolos de forma cirúrgica.


Programação Baseada em Eventos (Event Listeners):


O evento click no botão processa as contas matemáticas imediatas.


O evento change no <select> altera dinamicamente os nomes das moedas, troca os arquivos de imagem das bandeiras e refaz o cálculo de conversão automaticamente.


Tecnologias Utilizadas

HTML5 (Estruturação Semântica)

CSS3 (Flexbox, Efeitos de Transição e Design Responsivo)

JavaScript (ES6+) (Manipulação de DOM, Event Listeners e Intl API)

Google Fonts (Tipografia Roboto)

Previa:
<img width="958" height="416" alt="image" src= <img width="958" height="416" alt="conversor" src="https://github.com/user-attachments/assets/a8a11b89-de9e-4c05-8a24-f9350a4b3fdd" />
/>
