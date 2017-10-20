

#ATAJOS EN GNU/LINUX

En notación de Backus-Naur

![Icono GDM] (./ignu.png Viva Gnu)

##GNOME

    Meta: abre panel lateral
    Control Q: quitar programa
    Control W: cerrar ventana
    Alt Tabulador: alternar entre programas
    Alt y tecla de encima del tabulador: Alternar entre dos ventanas del mismo programa
    Control ALT ↓: cambiar entre escritorio
    meta espacio: Cambio de idioma
    Meta : maximizar ventana

##TEXTO

    Control +: Ampliar fuente
    Control -: Reducir fuente
    Control c: copiar
    Control v: Pegar
    Control X: Cortar
    Shift ←↑→↓: Subrayar de carácter en caracter
    Control Shift ←↑→↓: Subraya palabras enteras
    Control ALT O (vocal): pasar a modo pagina web

##Terminal

    Control alt T: Sacar terminal
    Control mayus t: abrir otra pestaña
    Alt nº: Cambias a la pestaña X
    Control mayus P: instalador paquetes, dentro de el en Package control: install Package y desde ahi tienes paquetes

    Control mayus U Nº: Metemos caracter unicode

    Control C: interrumpir un programa

    Control Z: Pasar a segundo plano

    fg 1: vuelve a primer plano

    Control mayus C: Copiar

    Control mayus V: Pegar

    Control l: Borrar pantalla

    Display: visor de imagenes

    Control D: terminar fichero

    y luego tenemos readline


    rm -rf

    
    git: 
    clone
    commit
    status
    add
    pull
    push
    git add -u(remove deleted files)
    seq: secuencia de numeros
##Comandos que unen
    cat: concatenar archivos en la terminal
    paste: unir en vertical
        ej: Tantor 0
    join: combinacion
##Comandos que dividen
    Cut: corta vertical cut -d" " -f 1
    split: divide horizontal
    tail -2 archivo
    tail -f (deja el fichero abierto)
    head
##Comandos que filtran



##METACARACTERES
    ~ home
    .: directorio actual
    ..: directorio de arriba
    -- (a veces el fichero que representa a la terminal)

wget + URL para descargar archivos
man 1 time herramientas de terminal
man 2 time nucleo sistema operativo
man 3 time lenguaje de programacion
Tambien se puede utilizar info
-b para separar x lineas se puede poner le tamaño que lo quieres separar ej: 2MB

mv: cambia el nombre o mueve de sitio un archivo.
traducir: cat nombre archivo | tr "lo que quieras cambiar" "a lo que cambia"       Para hacer rangos por ejemplo A-Z lo cambias por a-z
-s squeeze: apretar : cat nombrearchivo | tr -s "lo que quieras cambiar" "a lo que cambia"
uniq -c: Deja filas unicas -c: cuenta
sort: ordena. -n: numerico
telnet: lo que se escribe se manda a otro ordenador. 
- ssh: igual que telnet pero en modo seguro
