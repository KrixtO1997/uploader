# tguploaderpro
Bot De Telegram : TGUploaderPro v7.0 Fixed , Descargador gratis de contenido desde internet a hacia moodles , nexcloud en cuba

# Deploy Usando Git Win Y Heroku Cli Desde PC
```
(CMD)
git clone https://github.com/KrixtO1997/uploader
git init
git add .
git commit -m "OK"
heroku create myherokuapp
heroku git:remote myherokuapp
git push heroku master
```

# Comandos En El Bot (Usuarios Nomales)
```/start : Inicar Bot , Muestra la información de bienvenida al Bot
/tutorial : Muestra un tutorial básico de uso del bot.
/myuser : Obtiene la información del usuario que está utilizando el Bot
/zips : Configura el tamaño de las partes comprimidas 7z
/account: Configura su cuenta de nube en el Bot
/host : Configura el Host al cual se va a subir los archivos por ejemplo https://moodle.uclv.edu.cu/ (Moodle o Nexcloud)
/repoid : Cambia el repid de la moodle (En el caso de las moodles cada nube tiene su repoid q hay q saber extraerlo para poder configurarselo al Bot)
/cloud : Alterna el tipo de subida a nubes ya sea cloud o moodle , en caso de cloud es nexcloud pero para simplificar se pone cloud
/tokenize_on : Enciende el modo tokenize , se recomienda no usar a no ser q disponga de una de las apps oficiales de descarga del bot 
/tokenize_off : Apaga el modo tokenize
/uptype : Configura el modo de subir de moodle ya sea draft , evidence , blog y calendario
/proxy : Configura un Proxy para las subidas del Bot 
/files : En caso de tener activa el uptype (evidence) este comando le da una lista de archivos que se encuentra en las evidencias de la nube
/delall : En caso de tener activa el uptype (evidence) este comando borra todos los archivos en la lista de evidencia de la nube
/dir : En caso de tener activo cloud configura el directorio base en la nexcloud donde se van a subir los archivos
```

# Comandos En El Bot (Administrador) 
```/adduser : Permite a un usuario de telegram tener acceso al Bot
/banuser : Quita el acceso al Bot de un usuario de telegram
/getdb : Obtén la base de datos donde se almacenan la info de los usuarios en el Bot
```
# Deploy Directo (Heroku)
[![Heroku Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/KrixtO1997/uploader)
