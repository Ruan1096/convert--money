
O Convert Money é uma aplicação web responsiva voltada para a conversão de moedas em tempo real. Desenvolvido com HTML5, CSS3 e JavaScript puro (ES6+), o projeto simula a conversão do Real Brasileiro (R$) para o Dólar Americano (US$) e o Euro (€).

A lógica da aplicação foca na manipulação dinâmica do DOM para atualizar a interface instantaneamente sem recarregar a página. O grande destaque técnico está no uso da API Intl.NumberFormat, que garante a formatação cirúrgica e realista dos valores e símbolos monetários de acordo com o padrão internacional de cada região (pt-BR, en-US e de-DE). Além disso, o sistema conta com uma interface moderna centralizada com Flexbox e atualizações dinâmicas de textos e bandeiras baseadas em eventos do usuário.


Previa :


<img width="958" height="416" alt="conversor" src="https://github.com/user-attachments/assets/271893c7-2544-4086-ae81-2618a76b922e" />




🛠️ Destaques Técnicos
1. Interface e Estrutura (HTML5)
Semântica: Uso de <main> e <section> para separar a área de inputs da exibição de resultados, melhorando a acessibilidade.

Validação: Inputs configurados estritamente como number para evitar entradas de texto inválidas.

2. Layout e Identidade Visual (CSS3)
Flexbox: Posicionamento e alinhamento do cartão do conversor perfeitamente centralizado na tela.

Microinterações: Efeitos de transição suave (transition, :hover e :active) no botão de conversão para melhorar a experiência do usuário (UX).

3. Lógica e Dinamismo (JavaScript ES6+)
Manipulação do DOM: Atualização imediata dos dados na tela sem necessidade de recarregar a página (Single Page behavior).

Internacionalização (API Intl.NumberFormat): Formatação monetária precisa seguindo as regras de cada região (pt-BR, en-US e de-DE), aplicando símbolos e separadores corretos de forma cirúrgica.

Eventos (Event Listeners):

O evento click processa os cálculos matemáticos na hora.

O evento change altera dinamicamente os nomes das moedas, as imagens das bandeiras e atualiza o cálculo automaticamente ao trocar de moeda.

🚀 Tecnologias Utilizadas
HTML5 (Estruturação)

CSS3 (Flexbox e Efeitos Visual)

JavaScript (ES6+) (Manipulação de DOM, Eventos e Intl API)

Google Fonts (Tipografia Roboto)





