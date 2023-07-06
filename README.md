# PythonDados
Este código em Python utiliza as bibliotecas Beautiful Soup, Pandas e openpyxl para buscar dados de um site específico, extraindo o HTML dele.
Primeiro, é feita uma requisição HTTP ao site desejado usando a biblioteca requests. 
A resposta da requisição é armazenada na variável "response". Em seguida, o conteúdo HTML é extraído da resposta usando o atributo "content" e é atribuído à variável "html".
Depois disso, o Beautiful Soup é utilizado para analisar o HTML. 
A biblioteca cria uma representação estruturada do HTML, facilitando a extração dos dados desejados. 
Aqui, é utilizado o analisador "html.parser" para processar o HTML.
Por fim, os dados necessários são extraídos do site usando métodos do Beautiful Soup. 
Esses dados podem ser manipulados e armazenados em um formato mais conveniente, como um DataFrame do Pandas.
