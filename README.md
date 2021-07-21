## Projeto-previsao-do-tempo
### Projeto previsão do tempo da semana 7 projetos JavaScript da B7WEB

Projeto usando uma api estarna para verificar a temperatuda em qualquer cidade do mundo.
Utilizamos a api do site <https://openweathermap.org/>
Ao entrar no site, criar uma conta e gerar sua própria api key.

Inserir sua api key na variavel **myKey**:
~~~javascript
const myKey = "";
let url = `https://api.openweathermap.org/data/2.5/weather?q=${encodeURI(input)}&appid=${myKey}&units=metric&lang=pt_br`;
~~~
