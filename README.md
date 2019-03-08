cd /client 
npm install


https://www.youtube.com/watch?v=J7pFiXh-ydA
# Guest Map 


* App detect userts location ( from browser or IP)
* Guest of the website can leave a message 
* A pin will be added to the map with the userts location and message 


** TODO
Páginas
https://react-leaflet.js.org/docs/en/intro.html


[x]create-react-app 
    npx create-react-app client
    Ejecutar 
        cd /client
        npm start



[x]Install react-leaflet: https://github.com/PaulLeCam/react-leaflet
*     Instalar emojisense 
    * Descargar emojisense en visual studio code
    * settings>Extensions>:emojisense:   > Edit in settings.json 
"emojisense.languages": {
    "markdown": true,
    "git-commit": false,
    "plaintext": false,
    "json": true,
    "javascript": true
  },
"javascript.validate.enable": false
* npm install leaflet
    * import 'leaflet/dist/leaflet.css'
*  npm install react-leaflet



[x]Get a map on the page!
*     https://react-leaflet.js.org/docs/en/examples.html > A simple Marker with Popup
* npm start


Con estos paquetes no se muestra el mapa correctamente 
// {
//   "name": "client",
//   "version": "0.1.0",
//   "private": true,
//   "dependencies": {
//     "leaflet": "^1.3.4",
//     "react": "^16.8.4",
//     "react-dom": "^16.8.4",
//     "react-leaflet": "^2.1.2",
//     "react-scripts": "2.1.5"
//   },
//   "scripts": {
//     "start": "react-scripts start",
//     "build": "react-scripts build",
//     "test": "react-scripts test",
//     "eject": "react-scripts eject"
//   },
//   "eslintConfig": {
//     "extends": "react-app"
//   },
//   "browserslist": [
//     ">0.2%",
//     "not dead",
//     "not ie <= 11",
//     "not op_mini all"
//   ]
// }


[x]Get the users location 
    [x] with the browser
            https://developer.mozilla.org/es/docs/WebAPI/Using_geolocation
    [x]with their IP using an API 
            https://ipapi.co/json Obtiene mis datos georaficos a partir de mi ip publica



[x]Show a pin at the users location 



[x]Show a form to submit a message 
*when form is submitted - POST / message 



[]Setup server with create express-api: https://www.npmjs.com/package/create-express-api



[]Add monk and joi 



[]POST / messages 
* latitude
* longitude 
* name 
* message 
* datetime



[]When the page loads get all messages 
    []GET / messages



[]Add pins ti the map 



[]Click a pin to see the message 



[]DEPLOY!
    []https://guestm.app
* Reactor React app 
    * separate components 
    * separate file for API requests 
    * separate file for Location requests





Stretch 

[]Allow user to drag pin 
[]Login 
[]Users have their own guest map with their own markers and unique URL 
