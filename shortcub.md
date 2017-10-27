

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
    $: Da el valor de una variable
    \`: ejecutar un comando y sustituir por el resultado
    &: ejecutar una cosa en segundo plano


echo $#: cantidad de parametros
#: muestra los parametros
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

##comandos que trabajan con texto
grep: filtra
ed: editor sin ventanas
sed: lo mismo
vi: mejorado
find: busca ficheros
xargs ejecuta con argumentos
which: Averiguar donde se ha instalado algo
  1> tubo 1
  2> tubo 2

##! Shebang: Interprete con el que hay que ejecutar un archivo.

\: Kryptonita, le quita el poder al siguiente caracter, de los metacaracteres
\\: Secuencia de escape.
"": Quitan el poder a casi todos los meta, menos al $
$#: se convierte en comentario
!!: el ultimo comando
!*: los ultimos parametros
'': quita el poder a todos los metas

*: cualquier secuencia de 0 o mas caracteres
*b: lo mismo pero solo b.
?: cualquier caracter
[]: comando de seleccion.
{}: combinaciones de secuencias.      ej:   echo ma{txo,che}te

for i in a e i o u; do echo $i; done
for i in a e i o u; do touch bab${i}lonia; done

##OPERADORES LOGICOS
&&: and
||: OR
!: NOT
obase ej:                  echo "obase=16"; 1389 | bc
ibase ej:                  echo "ibase=16"; 56D | bc



date: poner la fecha
history: saca todos los comandos que has usado
mysqldump: volcado de la base de datos
rsync: hace copias de seguridad (varios equipos)


comando fg <n>; trae un proceso a primer plano
jobs: lista todos los procesos detenidos
ps aux: vemos los procesos
kill <nº proceso>: matamos el proceso
kill-9 <nºproceso>: matar por la fuerza