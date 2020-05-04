# ArgentoPack
Sonidos Argentos para conversaciones de Age of Empires II HD (2013)
"El Se�or Pack" by ChefeIdon


## Instalacion Windows
	
1- Descomprimir el archivo zip 
<img src="./preview.png" width="400">

2- Tendras que ubicar la carpeta donde esta Age of Empire 2 instalado

    normalmente suele ser:
    "C:\Program Files (x86)\Steam\steamapps\common\Age2HD"

3- Copiar la carpeta 'taunt' del archivo que descargaste y pegala en:

	"\Age2HD\resources\es\sound\"

    (ANTES RENOMBRA LA CARPETA ORIGINAL POR "taunt-backup")

4- Copia el archivo "key-value-strings-utf8.txt" y pegalo en:

    "resources/es/strings/key-value/"

    (ANTES RENOMBRA ARCHIVO ORIGINAL POR "key-value-strings-utf8-backup.txt")

5- Enjoy

## Instalacion Linux

1- copia y pega los siguientes comandos en una terminal

    git clone https://github.com/ChefeIdon/ArgentoPack.git
    cd ArgentoPack
    mv ~/.steam/steam/steamapps/common/Age2HD/resources/es/sound/taunt ~/.steam/steam/steamapps/common/Age2HD/resources/es/sound/taunt_back
    cp taunt ~/.steam/steam/steamapps/common/Age2HD/resources/es/sound/
    mv ~/.steam/steam/steamapps/common/Age2HD/resources/es/strings/key-value/key-value-strings-utf8.txt .steam/steam/steamapps/common/Age2HD/resources/es/strings/key-value/key-value-strings-utf8-backup.txt
    cp key-value-strings-utf8.txt .steam/steam/steamapps/common/Age2HD/resources/es/strings/key-value/

2- Listo el pollo amigueros.



#No me lo agradezcan a mi, agradezcanselo a mi navaja.