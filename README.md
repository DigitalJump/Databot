# Databot

## ¿Qué es Databot?

## ¿Como puedo tener databot en mi sitio o aplicación web?
Instalar databot es muy facil, tomará menos de 5 minutos
- Registrate en databot.cl
- Crea tu bot e inscribe tu plan
- Da click a ¡Quiero implementar! y copia el script de implementación 
- Pega el script de implementación antes del fin del body de tu sitio web y databot estará listo para responder las dudas de tus clientes o visitantes.
### Tu script lucirá así
```javascript
<script type='text/javascript' src='https://databot-api.herokuapp.com/dist_files/databot.js' id='50' bot='KNGHIZPLOLG'></script>
<link rel='stylesheet' href='https://databot-api.herokuapp.com/dist_files/databot.css'>
</body>
</html>
 ```
  
   
## ¿Como instalo Databot si mi proyecto está hecho en Nuxt.js?
- Entra a tu archivo nuxt.config.js
- Ve al objeto "head", y crea el array "script" dentro de este, en el agrega un objeto con los atributos src igual a https://databot-api.herokuapp.com/dist_files/databot.js, id: id_de_tu_bot, bot: token_de_tu_bot, body:true
- Ve al array "link", crea un objeto con atributo "rel" igual a "stylesheet", "href" igual a 'https://databot-api.herokuapp.com/dist_files/databot.css'

### Ejemplo
```json
  script: [
      { src:'https://databot-api.herokuapp.com/dist_files/databot.js', id:'55', bot:'KNGHIZPLOLG', body: true },
    ],
    link: [
      { rel: 'stylesheet', href: 'https://databot-api.herokuapp.com/dist_files/databot.css' }
    ]
 ```
