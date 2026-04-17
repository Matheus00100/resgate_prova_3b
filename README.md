Matheus Henrique Rossi : Problemas encontrados: 1. A página abria vazia (Carregamento Automático)O erro: Quando eu abria o ficheiro HTML, a lista não aparecia. Tinha de carregar sempre no botão "Buscar" para ver alguma coisa, o que não era prático.A solução: Adicionei a linha window.onload = buscarDados; no final do meu código JavaScript. Agora, assim que a página termina de carregar, a função corre sozinha e os dados aparecem logo, sem eu ter de clicar em nada.

2. O erro: O código original só mostrava o título do post. Ficava muito incompleto e não dava para perceber bem o que era cada item.A solução: Alterei a lógica do .map() para ir buscar também o ID (número do post) e o Body (o texto descritivo). Usei etiquetas HTML como <strong> para o título e <p> para a descrição, para ficar tudo bem organizado e fácil de ler.


3. O conteúdo estava todo em inglês (Tradução e Interface)O erro: Como a API que usámos é estrangeira, os dados vinham em inglês e a interface (botões e títulos) também não estava no nosso idioma.A solução: Traduzi toda a interface (como o botão "Buscar" e o título principal) e adicionei palavras em português antes das informações da API (por exemplo, mudei para aparecer "Postagem #" em vez de apenas o número), para que qualquer pessoa consiga entender o que está a ler. 


No final tudo foi resolvido, e rodou perfeitamente.
