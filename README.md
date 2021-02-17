# ArgentoPack
Sonidos Argentos para conversaciones de Age of Empires II HD (2013)
"El Señor Pack" by ChefeIdon


## Instalacion Windows
	
1- Descomprimir el archivo zip 

<img src="./Images/download.png">

2- Tendras que ubicar la carpeta donde esta Age of Empire 2 instalado

    normalmente suele ser:
    "C:\Program Files (x86)\Steam\steamapps\common\Age2HD"

3- Entrar a la carpeta en donde se encuentran los archivos de audio del juego:

	"\Age2HD\resources\es\sound\"

4- Elimina la carpeta 'taunt' existente.

5- Copiar la carpeta 'taunt' del archivo que descargaste y pegala en:

	"\Age2HD\resources\es\sound\"

4- Copia el archivo "key-value-strings-utf8.txt" y pegalo en:

    "resources\es\strings\key-value\"

    (ANTES RENOMBRA ARCHIVO ORIGINAL POR "key-value-strings-utf8-backup.txt")

5- Enjoy

## Instalacion Linux

1- copia y pega los siguientes comandos en una terminal

    git clone https://github.com/ChefeIdon/ArgentoPack.git
    cd ArgentoPack
    mv ~/.steam/steam/steamapps/common/Age2HD/resources/es/sound/taunt ~/.steam/steam/steamapps/common/Age2HD/resources/es/sound/taunt_back
    cp -r taunt ~/.steam/steam/steamapps/common/Age2HD/resources/es/sound/
    mv ~/.steam/steam/steamapps/common/Age2HD/resources/es/strings/key-value/key-value-strings-utf8.txt ~/.steam/steam/steamapps/common/Age2HD/resources/es/strings/key-value/key-value-strings-utf8-backup.txt
    cp key-value/key-value-strings-utf8.txt ~/.steam/steam/steamapps/common/Age2HD/resources/es/strings/key-value/

2- Listo el pollo amigueros.

## Desinstalación

Para desinstalar los sonidos, solo debes ir a las propiedades del juego desde Steam, en la pestaña de Archivos locales tocar en 'Verificar Integridad de Archivos'. Steam descargará los archivos originales y borrará el ArgentoPack.


# No me lo agradezcan a mi, sino a mi navaja.

Este pack de sonidos se distribuyen gratuitamente y sin garantia alguna, usar responsablemente
