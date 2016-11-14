# Google Maps (Gmaps API): How to create routes, save using localstorage, add marks, etc.
Google Maps (Gmaps API): How to create routes, save using localstorage, add marks, etc.<br>
Google maps (Gmaps API): Añadir rutas, guardarlas usando localstorage, añadir marcas, etc.<br><br>

[ESP]
- Puedes crear rutas clicando con el ratón (múltiples rutas).
- El botón "Compactar" se centrará en la ruta inicio y destino (borrando las que haya por el camino, o las anteriores al destino). Al mismo tiempo guardará los valores en localStorage.
- El botón "Borrar ruta" borrará los valores y mostrará el origen de Gmaps (default). Al mismo tiempo borrará de localStorage los parametros de longitud y latitud que guardaban la ruta en compactar.
<br><br>
[EN]
<strong>Creating a route with a click (multiple marks for multiple clicks):<br></strong>
![Alt text](https://cloud.githubusercontent.com/assets/14861253/20276300/f6176608-aa9b-11e6-8e6c-b87888b8fd58.png)<br><br>

<strong>"Compactar" button will erase all marks, showing origin and destiny (latitude and longitude using localstorage):<br></strong>
![Alt text](https://cloud.githubusercontent.com/assets/14861253/20276419/70edf770-aa9c-11e6-9c4f-cedb69ea85b9.png)<br><br>

<strong>"Borrar ruta" button will erase all marks, showing just the origin where you are (also, will delete longitude and latitude parameters from the localstorage).</strong><br>
![Alt text](https://cloud.githubusercontent.com/assets/14861253/20276426/7879f1ce-aa9c-11e6-8b22-599a1e1aa23e.png)<br><br>

