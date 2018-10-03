Enfermera Joy es un bot especializado en gestionar grupos de Pokémon GO en Telegram.

Puedes pedir ayuda en el grupo [@enfermerajoyayuda](https://t.me/enfermerajoyayuda) y estar informado de las novedades en el canal [@enfermerajoynoticias](https://t.me/enfermerajoynoticias).

1. [Ayuda para entrenadores](#ayuda-para-entrenadores)
   1. [Registrarse en el bot](#registrarse-en-el-bot)
   2. [Profile](#profile)
   3. [Iconos en la Ficha de Entrenador](#iconos-en-la-ficha-de-entrenador)
   3. [Código de Entrenador](#código-de-entrenador)
   4. [Quién es](#quién-es)
   5. [Tablas](#tablas)   
   6. [Más ayuda](#más-ayuda)
2. [Ayuda para administradores](#ayuda-para-administradores)
   1. [Añadir el bot a un grupo o canal](#añadir-el-bot-a-un-grupo-o-canal)
   2. [Configuración](#configuración)
   3. [Modo enfermera](#modo-enfermera)
   4. [Tipo de grupo](#tipo-de-grupo)
   5. [Zona horaria](#zona-horaria)
   6. [Bienvenida](#bienvenida)
   7. [Otros comandos exclusivos para administradores](#otros-comandos-exclusivos-para-administradores)
3. [Reglamento General de Uso del Bot](#reglamento-general-de-uso-del-bot)
4. [Política de privacidad](#políica-de-privacidad)

## Ayuda para entrenadores ##

### Registrarse en el bot ###

El registro puede ser obligatorio en algunos grupos (todo depende de la configuración del grupo), pero para poder interactuar con el bot, es imprescindible el registro.

Registrarte te permite disfrutar de todas las funcionalidades del bot, como por ejemplo preguntar por otros usuarios, solicitar información de los Pokémon y muchas más funcionalidades que llegarán en un futuro.

Para registrarte tienes tres opciones:

1. La opción más rápida, si estás registrado con [@detectivepikachubot](https://t.me/detectivepikachubot), es decirle por privado a [@NurseJoyBot](https://t.me/NurseJoyBot) el comando `/register`, entonces te preguntará si quieres que le pregunte a Detective Pikachu tus datos. Si aceptas tendrás que abrir la conversación privada con Detective Pikachu que te preguntará lo mismo. Si aceptas en ambos entonces ya estarás registrado.

   Si antes de eso ya le habías dicho a Detective Pikachu que aceptas compartir los datos con Enfermera Joy, entonces al escribirle        `/register` preguntará automáticamente los datos a Detective Pikachu (sin que tu tengas que hacer nada) y ya estarás registrado.

2. Si al decirle `/register` en privado a [@NurseJoyBot](https://t.me/NurseJoyBot) no estás registrado con el bot [@detectivepikachubot](https://t.me/detectivepikachubot) o no has aceptado que Enfermera Joy pregunte los datos a Detective Pikachu, entonces iniciará automáticamente el proceso de registro en el cual te preguntará tu nick de entrenador y te pedirá que hagas una captura de pantalla del juego con unas condiciones.

3. También tienes la opción de que si estás registrado y validado con [@detectivepikachubot](https://t.me/detectivepikachubot), puedes escribir el comando `/profile` en el privado de Detective Pikachu y reenviar la respuesta a [@NurseJoyBot](https://t.me/NurseJoyBot). Este método, sirve tanto para registrarse como para subir de nivel.


### Profile ###

El comando `/Profile` puede utilizarse en un grupo o en una conversación privada con el bot [@NurseJoyBot](https://t.me/NurseJoyBot), pero la resupesta de Enfermera Joy será enviada al privado. Este comando hará que el bot responda con la Ficha de Entrenador (Nick del juego, Equipo, Nivel y Estado de Validación) del jugador que la solicita.

Ejemplos de posibles respuestas del bot:

1. **Berny**, eres del equipo **Instinto** nivel **40** ✅
   
   Estás registrado correctamente.

2. *Desconocido*, es *Desconocido* nivel *Desconocido*.

   Esto quiere decir que el proceso de validación ha sido iniciado pero no finalizado, por lo tanto no estás registrado con el bot.

3. X No tengo información sobre ti.
   
   No tiene ningún tipo de dato sobre ti.


### Iconos en la Ficha de Entrenador ###

En principio, el único icono que deberías de ver ya sea en tu Ficha de Entrenador o en la de tus companeros es el de Validado (✅), pero existen mucho otros.

Algunos de ellos son los siguientes:

| Icono           | Definición                       |
|:----------------|:---------------------------------|
|        .        | Baneado                          |
|        .        | Staff                            |


### Código de Entrenador ### 

Si quieres, puedes compartir tu código de entrenador con el bot para que cuando pregunten por ti con el comando `quién es` (para más información sobre este comando mira el apartado [Quién es](#quién-es)), aparezca junto al resto de información. Únicamente verán tu código aquellas personas que hayan compartido el suyo con el bot.

Para compartir tu código de entrenador, lo debes hacer con el siguiente comando (el número sin espacios y separado del comando):

    /set_friendid 

Una vez hecho esto, para ver los codigos de entrenador de los demás, tienes dos formas:

`(no disponible)` - Este comando es **exclusivo** para grupos. El bot te enviará un listado de todos los IDs conocidos del grupo por privado.

`(no disponible)` - Respondiendo a un mensaje de alguien, Joy te enviará por privado la información de ese usuario.


### Quién es ###

El comando `quién es` (también aceptado como `quien es` o `/whois`, sin interrogante) hace que el bot te responda la información de la Ficha de Entrenador (Nick del juego, Equipo, Nivel y Estado de Validación) del jugador solicitado.

Ejemplos de posibles respuestas de Joy:

1. **Berny**, es del equipo **Instinto** nivel **40** ✅

   El Entrenador utiliza el nick de Berny en el juego, es del equipo Instinto, nivel 40 y está validado. Aunque no es freqüente, la        Ficha de Entrenador puede tener otros iconos. Para más información leer el apartado [Iconos en la Ficha de Entrenador](#iconos-en-la-ficha-de-entrenador).

2. X No tengo información sobre este entrenador.
   
   El Entrenador no está registrado.

3. *Desconocido*, es *Desconocido* nivel *Desconocido*.

   El Entrenador ha iniciado un proceso de registro, pero no se ha terminado correctamente.

El bot siempre enviará la información al privado, por ello es imprescindible tener abierta una conversación privada con [@NurseJoyBot](https://t.me/NurseJoyBot).

Se puede emplear el comando de dos formas:

1. Citando el mensaje del jugador por el grupo general y escribiendo el comando. El bot eliminará automáticamente el mensaje donde esté el comando y responderá con un mensaje que también será eliminado cuando hayan pasado unos segundos.

2. Citando el mensajde del jugador por privado. Este método evita escribir el mensaje por grupo, pero es algo más rebuscado. Primero de todo se debe reenviar un mensaje del jugador que se desea al privado del bot [@NurseJoyBot](https://t.me/NurseJoyBot), seguidamente, dentro del privado del bot, deberás citar el mensaje que acabas de reenviarle y escribir el comando.


### Tablas ###

El bot dispone de una gran cantidad de tablas de IV, de recompensas por amistad, Pokémon de los Community Day, Pokémon shiny, etc. Para solicitarlas se debe emplear el comando `/tabla` o `/table` seguido de un espacio y el nombre de la tabla que se desea. El mensaje solicitando la tabla será eliminado por el bot de forma automática.

Todas las tablas son mandadas al privado del bot, para ello es necesario tener abierta una conversación privada con [@NurseJoyBot](https://t.me/NurseJoyBot).

Estos son las tablas de las que se disponen actualmente:

- Absol
- Articuno
- Beldum (también la puedes solicitar como Community)
- Celebi
- Deoxys normal
- Entei
- Golem
- Groudon
- Ho-oh
- Kyogre
- Lapras
- Latias
- Latios
- Lugia
- Machamp
- Magikarp
- Marowak (alola)
- Mawile
- Mew
- Mewtwo
- Moltres
- Raichu (alola)
- Raikou
- Rayquaza
- Regice
- Regirock
- Registeel
- Rhydon
- Snorlax
- Suicune
- Tyranitar
- Zapdos

***

- Amistad
- Community

Todas las tablas se van modificando según los cambios que van surgiendo en Pokémon Go y se van añadiendo tablas nuevas necesarias, por lo tanto la lista de tablas es algo que irá cambiando.


### Más ayuda ###

Si necesitas ayuda que no se encuentre en este manual, puedes preguntar en [@enfermerajoyayuda](https://t.me/enfermerajoyayuda). Si estás administrando un grupo o un canal, continua leyendo para ver la ayuda para administradores.


## Ayuda para administradores ##

De aquí en adelante, [@NurseJoyBot](https://t.me/NurseJoyBot) pasará a ser *el bot*.

### Grupos ###

El soporte del bot, por el momento, solo está probado en **grupos y supergrupos**. En un futuro, contará con soporte en canales.

En **grupos** el bot ya se puede utilizar tan pronto entra al grupo y envía un saludo. Conviene configurarlo, no obstante. Ten cuidado porque, si una vez añadas el bot conviertes el grupo a supergrupo, tendrás que volver a configurarlo. Un supergrupo es la mejor opción en la mayoría de los casos.

### Añadir el bot a un grupo o canal ###

Para **añadir el bot a un grupo** tienes tres alternativas:

1. Dirígete al perfil del bot. En el menú, selecciona la opción *Añadir a un grupo* y escoge el grupo de la lista.

2. Pulsa en [este enlace](https://telegram.me/NurseJoyBot?startgroup=true) en un dispositivo donde tengas Telegram instalado.

3. Puedes intentar añadirlo como un contacto más desde el grupo con su alias `@NurseJoyBot`, pero en versiones recientes de Telegram hay problemas usando este método.

### Configuración ###

Para hacer la configuración básica del bot utiliza el comando `/settings`. La configuración está dividida en varios apartados:

1. **Chistes**. Activa o desactiva los chistes, refranes y cualquier cosa que pueda hacer que el bot hable sin que nadie lo invoque. Opción desactivada por defecto.

2. **Juegos**. Permite o no que los usuarios ejecuten los comandos para jugar con el bot. Opción desactivada por defecto.

3. **Modo enfermera**. Borra todos los mensajes a excepción de los enviados por administradores. Mira el [apartado del modo enfermera](#modo-enfermera) para más información. Opción desactivada por defecto.

4. **Tipo de grupo**. Cuenta con cinco opciones. Mira el [apartado del tipo de grupo](#tipo-de-grupo) para más información. Opción desactivada por defecto.

5. **Configuración de los avisos**. Esta función sirve para determinar el número de avisos que recibirá un usuario antes de ser expulsado de un grupo. Las diferentes opciones son 5/10/25/50/100.

### Modo enfermera ###

El modo enfermera evita que la gente hable en un grupo, borrando todos los mensajes que pongan los usuarios (no los administradores).

El comando `/settalkgroup` permite definir un grupo para hablar.  Por ejemplo:

    /settalkgroup @enfermerajoyayuda
    /settalkgroup https://t.me/joinchat/XXs3XkzYsXXxnvbtxxe11x

Si está el modo enfermera activado, el bot recordará el enlace al grupo para hablar cada vez que hable alguien.

### Tipo de grupo ###

Por defecto al introducir el bot, se establece el grupo como *grupo sin requisitos*

| Identificador   | Definición                       |
|:----------------|:---------------------------------|
|        ▪️        | Grupo sin requisitos             |
|       ✅       | Grupo con validación obligatoria |
|       ❤️       | Grupo exclusivo Rojo             |
|       💙       | Grupo exclusivo Azul             |
|       💛       | Grupo exclusivo Amarillo         |

En caso de que un usuario intente acceder a un grupo en el cual no cumpla las condiciones de entrada, si el bot cuenta con los privilegios pertinentes, expulsará al usuario.

### Zona horaria ###

El bot reconoce la hora que escriben los usuarios y hace operaciones con ellas, por lo que es importante que la hora que utilice el bot se corresponda con la hora real de tu grupo.

Para establecer la zona horaria correcta se debe utilizar el comando `/settimezone` con la zona horaria correspondiente como parámetro siguiendo el formato del [listado de zonas horarias de la IANA](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones). Por ejemplo:

    /settimezone Europe/Madrid
    /settimezone Atlantic/Canary

### Bienvenida ###

El bot puede dar la bienvenida a los entrenadores que vayan entrando al grupo.

Para poder definir el mensaje de bienvenida del bot es necesario utilizar el comando `/set_welcome`. Por ejemplo, si se quiere poner el mensaje "Bienvenidos al grupo", sería:

    /set_welcome Bienvenidos al grupo.

Además el bot dispone de tres strings que se pueden introducir en el texto de bienvenida para conocer más información del entrenador que acaba de entrar. Por ejemplo:

| Strings   | Texto mostrado       | Definición                              |
|:----------|:---------------------|:----------------------------------------|
|   $pogo   | Berny **L40** 💛 ✅ | Nick +Nivel +Equipo +Proceso validación |
| $username | Berny                | Nick                                    |
|  $title   | PoGo de tu ciudad    | Nombre del grupo                        | 

Para poner links en el mensaje de bienvenida lo puedes hacer mediante el siguiente string: `[NombreLink](Link)`.
Por ejemplo: `[superjoy](https://websuperenfermerajoy.com)`. Este link que veremos en el mensaje de bienvenida como `superjoy` al clickarlo nos mandará a la web `https://websuperenfermerajoy.com`.

Si se quiere eliminar el mensaje de bienvenida, para que el bot deje de saludar cuando entren entrenadores nuevos, entonces se debe escribir el comando `/set_welcome` sin ningún texto más.

### Otros comandos exclusivos para administradores ###

`/ban`: Expulsa y banea al usuario en el grupo actual. Se utiliza respondiendo a un mensaje del usuario a banear.

`/kick`:  Expulsa al usuario en el grupo actual. Se utiliza respondiendo a un mensaje del usuario a expulsar.

`/warn`: Advierte al usuario en el grupo actual. Al alcanzar el nº máximo de advertencias banea al usuario del grupo. Se utiliza respondiendo a un mensaje del usuario a advertir.

## Reglamento General de Uso del Bot ##

El siguiente punto, detalla la normativa a cumplir en caso de registrarse en el bot. El desconocimiento de la misma no exime al usuario de su aplicación pues todas las normas aquí recogidas son de sentido común. 

Este bot no puede ser utilizado en grupos o canales que promueven el uso de trampas en el juego. Si bien no se puede evitar que sea utilizado casi por cualquiera, el bot implementa algunas medidas anti-trampas que detectan determinados comportamientos que pueden llevar a un baneo preventivo.

En caso de formar parte de un grupo en el cual se encuentre [@NurseJoyBot](https://t.me/NurseJoyBot) y conozcas a un usuario o administrador que no cumpla alguna de las normas, se deberá comunicar mediante correo electrónico a la dirección [reportes@qwert1.es](mailto:reportes@qwert1.es). Cualquier sanción aplicada será debatida entre los miembros del staff del bot, apelable en la siguiente dirección de E-mail: [apelaciones@qwert1.es](mailto:apelaciones@qwert1.es).

### Normas de Enfermera Joy ### 

- 🔞 Está totalmente prohibido enviar material sensible.
- ⛔️ Está **COMPLETAMENTE PROHIBIDO** solicitar y/o aportar información relativa a otro jugador en cualquiera de los grupos oficiales del bot o bien por privado a cualquier miembro del staff. En caso de producirse esta situación, los administradores se reservan el derecho de banear **definitivamente** la cuenta del entrenador.
- 😈 Nunca difames, abuses, hostigues, dañes, acoses, amenaces o violes de cualquier manera los derechos legales (incluidos los derechos de privacidad y publicidad) de los demás.
- 👺 Se ruega evitar generar discusiones o debates *interminables*, o que no aporten información útil al grupo, incluyendo temas de hacks, trampas, emuladores o similares.
- 😊 Ante todo, ¡fomenta el buen rollo! El grupo no es restrictivo, no tengas miedo de preguntar o conversar sobre el juego. Pero ten cuidado con las cosas o "bromas" que digas, puedes ofender a alguien.
- 📩 Se considera **flood** el hecho de repetir continuamente palabras, hacer *cadenas* de contenido multimedia o comandos (enviar muchas fotos o stickers seguidos), provocando molestias al grupo con contenido innecesario. 
- 🌍 Normalmente el usuario estará unido en los grupos cercanos a su ubicación, o que suela frecuentar. Si un usuario es avistado en varios grupos de diferentes ubicaciones a la vez, podría ser expulsado de todos ellos por sospechas de posibles trampas. Se entiende que si un usuario se va de vacaciones a otro lugar, no es necesario abandonar los grupos de su ubicación, y se valorará este motivo.


### Normas del Entrenador ###

Es **obligatorio** que todos los usuarios que están en el grupo, cumplan las [Normas del Entrenador](https://support.pokemongo.nianticlabs.com/hc/es/articles/221993967) de Niantic.

Obviando la parte de comportamiento ético como personas, se detalla que jugar de las siguientes formas (pero no únicamente éstas) se considera **trampa**, llevando a la expulsión del grupo:
- Usar software modificado o no oficial
- Compartir cuentas, jugar con cuentas de otros jugadores en un mismo móvil
- Usar herramientas o técnicas para alterar o falsificar la ubicación
- Vender y comerciar con las cuentas

Debido a la polémica generada con los usuarios que utilicen más de una cuenta o compartan la suya, a diferencia de lo que dicen las normas del entrenador, **NO** será sancionable a excepción de usuarios que abusen de estas o las utilicen con el fin de perjudicar a terceras personas.


## Política de privacidad ##

### Qué información recopilamos y sometemos a tratamiento ###

Este bot recoge la siguiente información sobre sus usuarios al interactuar con él en privado o a través de un grupo o canal de Telegram:

- Identificador numérico de Telegram
- Alias público de Telegram
- Estado de la cuenta (validada, no validada o baneada)
- Datos relacionados con la cuenta de Pokémon GO facilitados en el proceso de registro: equipo, nombre de entrenador y nivel

El bot también almacena unos ficheros no ordenados con las interacciones en grupos y directas (logs), con el objetivo de poder trazar problemas técnicos y atender a las apelaciones de baneo.

### Cómo se utiliza la información ###

La información almacenada se utiliza para los siguientes fines:

Ofrecer el servicio de gestión de grupos de Pokémon GO en Telegram.
La base legal para el tratamiento de datos mencionado en esta sección es la prestación del servicio que se solicita voluntariamente (artículo 6, párrafo 1 (b) del RGPD).

Como se explica en la Política de tramposos, se rastrearán los logs la actividad de forma automatizada en busca de sospechosa. La base legal para este tratamiento de datos es el artículo 6, párrafo 1 (f) del RGPD.

### Quién tiene acceso a la información ###

El alias público de Telegram y los datos relacionados con la cuenta de Pokémon GO podrán compartirse en grupos o canales en los que se mantenga actividad. Esta compartición puede ser pública, dependiendo de la configuración de cada grupo o canal.

El identificador numérico y alias público de Telegram y el nombre de entrenador de Pokémon GO podrán compartirse con los administradores de los grupos o canales en los que se realice alguna actividad.

La base legal para compartir los datos proporcionados es la prestación del servicio que se solicita voluntariamente (artículo 6, párrafo 1 (b) del RGPD).

### Duración del almacenamiento ###

La información se almacena durante el tiempo necesario para cumplir con los fines para los que se se recopila:

La información de la cuenta de Pokémon GO y alias de Telegram se eliminan al pasar seis meses desde la última participación en una incursión.
Las interacciones en grupos y directas con el bot (logs) se eliminan pasados dos meses.

### Derechos contemplados en el RGPD ###

Se debe enviar un correo a [apelaciones@qwert1.es](mailto:apelaciones@qwert1.es) indicando que se desea ejercer alguno de los derechos contemplados: acceso, rectificación, supresión y limitación del tratamiento, portabilidad de datos.

En caso de ejercitar el derecho de supresión, el bot guardará el identificador numérico de Telegram junto con una marca que indica este deseo. En este caso, no será posible utilizar el bot y el estado de la cuenta aparecerá como baneada.
