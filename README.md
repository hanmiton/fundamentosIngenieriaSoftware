Como funcionan las computadoras y los teléfonos y móviles
  1.- Señal del teclado
  2.- Motherboard
  3.- CPU
  4.- O.S (Drivers)
  5.- Google Chrome
  6.- Evento
  7.- Javascript
    - Ajax (Asyncronoums Javascript and xml)
    - json (formato de un archivo Javascript Object Notation)
    - REST (protocolo para enviar datos la servidor)
    - http (protocolo transferencia de hypertexto)
  8.- API (application program interface)
  9.- ftp (file transfer protocol)
  10.- telnet ssh (secure shell)
  11.- http (hypertext protocol)
  12.- https
    - La comunicacion va cifrado porq no viaja en linea recta
  13.- dominio (Ej: gmail.com)
    - lo entiende un dns que lo cambia por una ip
    - dns (domain name service)
    - ping google.com
  14.- servidor
    - donde se ejecuta el codigo Ej Java
  15.- Ethernet
    - tcp/ip
    - http
    - servidores nginx o Apache
    - Java( procesa la inforamcion recibida en json)
  16.- Lenguaje de programacion
    - java, php, python, go
  17.- Base de datos
    - Postgres, Oracle, Mysql
  18.- Correos
    cursos@mi_domino.com
    SMTP/POP3
    honypots, listas negras
    dificil alzar tu propio smtp
    Postfix (servidores de email)
      - Base de datos/bandeja
  19.- Servidores de notificaciones
    sabe endonde esta el dispositivo
    se subcriben al servicio para enviar la notificacion
    - notificacion server
      Telefono
      Id
      ip
    - Usa UDP (nunca espera respuesta)
    - Servidor de notificaciones envia notificacion al dispositivo
    Telefono
      System on a Chip en vez de CPU

CLASE 2
  Que son bits y bytes
  Electricidad funcionan en ondas
  señales se guarda en discos ldp como saltos
  Sonido
    hacer vibrar una menbrana segun la onda de la Electricidad
  Codigo MOrse
    mensajes largos y cortos
    no muy efectivo para grandes cantidades de informacion
  Tonos Electricidad  
    Alto 1
    Bajo 0
  Bit
    1 o 0
  IBM 1956
    byte
      de aceurdo a las patas del procesador
      se definio de 8 espacios
    bases numericas
      binaria
      decimal
      hexadecimal
    Assembler
      bytes especiales de instruccines de procesador
    TODO SON bytes  
      192.168.7.255 4 numeros q son bytes
      Imagen
        son pixeles y cada pixel = byte numero representa un color
        cada pixel es igual a 2 bytes
      Emojis
        Se agregaron a la tabla ascii
    UTF-8
      todo mundo usa la misma tabla ascii
    UTF-16
      nueva cantidad de bits q usan 2 bytes
      sobraba un espacio y lo usaron para Emojis
    UNICODE
      los q se encargan q añadir a la tabla ascii

Como funcionan circuitoso electricos
  Servos
    motores muy pequeños y muy precisos
  Ram
    guarda 0 y 1 mientras circuito tenga energia
  disco duro
    guardan 0 y 1 con o sin energia
  Procesadores
    los leguajes de programcion ayudan a procesar dichos 0 y 1 q recibe el procesador

Procesadores y arquitectura de CPU
  CPU
    intel, amd
    ghz
    cores (No de CPUs cuandas instrucciones ne paralelos q se puden hacer)
    silicio (grafeno)
  BIOS
    pequeño sistema operativo de arranque
    da señal de inicio a CPU
    detecta todas las cosas que estan conectadas
  DISCO DURO
    donde se encuentra el sistema operativo
    todas las aplicaciones
    conexion entre DISCO DURO y CPU
      antes pasa por la RAM
    mas lento q RAM
    porq el disco tiene un cabeza y tiene que tratar de encontrar el archivo con la cabez de lectura mientras ruede
    rpm mas rapido
    fragmetacion para que no se mueva cabeza de lectura tanto
  SSD
    no tiene partes moviles
    tienen un chip especial
    tecnologia de memorias usb
    chip flash
    la misma que en las sd
  RAM
    memoria que tenemos mientras estamos con conrriente trabajo
    memoria de muy alta velocidad
    promedio 16gb
    circuitos y transistores que lo tiene vivo en ese moment quimico EJ acido 1 no tan acido 0
  MENRISTOR
    piesa electronica que logra guardar la onda electrica q paso con ella y es igual de veloz q una ram
    remplazar disco y ram por una sola pieza electronica
  PERIFERICOS
    todas las cosas externas con als que se interactua con el computador
      pantalla
      mouse
      teclado
      puertos
  Drivers
    son piesas de codigo que permiten entender
    Pantalla
      gpu no tan rapido como CPU
      gpu realiza muchos procesos en paralelos
      gpu solo se dedica para mostrar en pantalla
      decodifican videso con un chip
  TARJETA Sonido
    viejo
    drivers speakers

SYSTEM ON A CHIP
  internet de las cosas IoT
  sistemas enteros en un chip
  raskberry
  CUP tiene memoria ram y pequeño disco duro y bios
  chip para usb
  chip para controlar todo lo electrico
  pines
    bus de datos con el se puede conectar el computador Ej pantalla

  System on a chip
    BIOS
    ram
    CPU
    radio (todas las señales de radio)
    gpu pantalla
    perifericos
  Bateria
    pesada
    controlador electrico(controla calor,conectado a electricidad )
  Pantalla
    no tienen todos
  INputs (se conecta a system on a chip)
    botones
    acelerometros
    brujulas
