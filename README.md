# SpotiCloud
Este proyecto fue desarrolado en 2019 como trabajo práctico de la materia Algoritmos y Programación I, de la Facultad de Ingenieria de la UBA. Los requerimientos se pueden leer en el [enunciado](enunciado.pdf).


## Características

### 1. Crear y Editar Playlists

Permite a los usuarios crear y editar playlists en su cuenta de Spotify directamente desde la línea de comandos.

### 2. Agregar Canciones a Playlists

Permite el agregado de canciones a las playlists existentes.

### 3. Obtener los Artistas Top de Diferentes Países

Accede a la API de Spotify para obtener información sobre los artistas más populares en distintos países.

### 4. Generar Playlists según el Clima

Integra la API de Open Weather para obtener información sobre el clima y crear playlists personalizadas basadas en las condiciones meteorológicas actuales.

## Requisitos

Asegúrate de tener instaladas las siguientes dependencias:

- Python
- Instala las bibliotecas necesarias ejecutando `pip install -r requirements.txt`

Además debes generarte una key para la API de Spotify y de OpenWeather.
- [Spotify for Developers](https://developer.spotify.com/)
- [OpenWeather API](https://openweathermap.org/api)

## Configuración

Antes de ejecutar la aplicación, asegúrate de configurar tus claves de API. Crea un archivo `.env` en la raíz del proyecto y agrega las siguientes variables:

```env
SCOPE = 'playlist-modify-public'
SPOTIPY_CLIENT_ID = 'your_spotify_client_id'
SPOTIPY_CLIENT_SECRET = 'your_spotify_secret_key'
USER = 'your_spotify_user_id'
OWMKEY='your_ow_secret_key'
```
Debes reemplazar los valores por tus propias claves.

## Uso
- Ejecuta python SpotyCloud.py desde la línea de comandos.
```bash
python SpotiCloud.py
```
- Sigue las instrucciones para autenticarte con Spotify.
- Utiliza las opciones del menú para acceder a las diferentes funciones del programa.
