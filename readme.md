
## Proceso de instalación 

* **Activar entorno virtual**
```
source <nombre_entorno_virtual>/bin/activate
```

* **Instalar "requirements":**
```
pip install -r requirements.txt
```

* **Crear variable de entorno**

Crear variable de entorno **FLASK_APP** con el valor **run.py**

* **Vincular API**

Iniciar sesion en CoinMarketCap para conseguir una APIKEY:
```
https://pro.coinmarketcap.com/login/
```
Crear un fichero con nombre **config.py** 
Introducir su APIKEY en el archivo **config.py**

El fichero deberá contener 
SECRET_KEY="Introducir la APIKEY que nos devulve CoinAPI.io"
API_KEY="Introducir la APIKEY que nos devulve CoinAPI.io"

* **Ejecutar aplicación**
```
flask run
```