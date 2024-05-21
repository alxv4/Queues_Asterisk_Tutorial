# simple_queues_Asterisk (Cola simple Asterisk )

[ESP]

Hola,

Este repositorio sirve como guía para que puedas aplicar de manera sencilla el uso de colas en Asterisk.

Estamos simulando una situación en la cual el LLAMANTE se comunicará con el servicio de soporte

que se encuentra en el anexo 5000,el IVR le indicará si es un cliente VIP o cliente CLÁSICO, dependiendo

de su elección marcará el botón 1 o 2 para luego serle asignado a alguna cola, la cola01 corresponde a la

cola VIP y la dos a la CLÁSICA.

En el archivo queues.conf ...

Existe un comando ...

=> ringinuse=no

... que evita el timbrado en algún teléfono que esté ocupado en una llamada dentro de cualquier cola.


/EXTRA/

Si deseas generarcon IA tus audios para usarlas en tu IVR puedes usar el siguiente link ...

=> https://textoavoz.net/

... eso permite que tu escribas el texto que quieras y lo transforma en voz con el idioma de cualquier país.

Cuando descargues el archivo verás que se guarda en formato .mp3, hasta donde sé debes guardarlo en formato .wav

entonces este link te puede servir ...

=> https://cloudconvert.com/

... Los parámetros que yo uso son:

Audio Codec: por defecto (pcm_s16le)

Audio Bitrate: 64

Channels: mono

Volumne: no change

Sample Rate: 8000 Hz


