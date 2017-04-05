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

    Aspectos importantes a tener en cuenta de la clase:
    Discos duros:

    Forma en que organizan datos:

    Persistente
    Secuencial
    Estructurada (Depende del sistema de archivos, que a su vez depende del S.O. que esté en el disco duro):
    Windows: FAT16 - FAT32, NTFS
    Linux: Ext3 - Ext4
    Mac OS: HFS, APFS
    Forma de localizar y leer archivos:
    En la parte superior de los Discos Duros existe una cabecera, la cual guarda el indice de todos los archivos, esto permite que en el momento de lectura desde la cabecera, se conozca en dónde está ubicado el archivo en cuestión.
    Borrado de archivos:
    Por tal motivo, cuando se “borra” un archivo, lo que realmente se esta haciendo es eliminando el indice en la cabecera que está relacionado con el archivo. Determinados tipos de software permiten la recuperación de estos archivos, leyendo detalladamente toodo el disco duro. Sin embargo algunas practicas de borrado (Sheredder) permiten borrar el archivo por completo, incluso ejecutando el borrado determinado número de repeticiones, lo que imposibilita el trabajo de forenses para la recuperación de datos o archivos.
    Memoria RAM (Random access memory)

    Procesos:
    La memoria RAM, siendo tan rápida, tiene la capacidad de ejecutar varios procesos paralelamente. El SO es uno de esos procesos ejecutados por la RAM. Sin embargo la opciones que nos ofrece el SO son muchas y no siempre se utilizan todas, por lo tanto la RAM solo carga aquellas tareas que realmente necesitamos y estamos usando frecuentemente.
    Localización de procesos:
    A diferencia de los discos duros, la memoria RAM hace uso de un indice compartido con la CPU que es ultra veloz. Esto facilita y permite una localización de los procesos por parte de la CPU de una manera increíblemente rápida.
    CPU (Central process unit):

    Dentro de este asombroso chip, no encontramos con un espacio que recibe por nombre Memoria Caché. En ella se guardan y almacenan cierto tipo de datos de uso frecuente, para que sea más fácil y rápido el acceso a ellos. Por ejemplo una parte del SO siempre estará almacenada en la Memoria Caché para que sea rápido acceder a él.
    Comunicación:

    Ram:
    Para lograr la efectiva comunicación entre la CPU y la RAM existe lo que se conoce como un bus de datos o bridge (puente). Un bus de datos en algunas ocaciones es un cable delgado y ancho. En otros casos esta conexión está establecida como circuito en la placa madre (mother board).
    Disco Duro:
    Para la conexión entre en disco duro y la CPU, el bus de datos recibió inicialmente el nombre ATA, que en una versión posterior se llamó SATA. Hay otro tipo de bus de datos para el disco duro mejor que SATA, que se llamó IDG.

GPU CLASE 5
  bus especial chip GPU (Graphic processor unit)
  mayor cores y mejor ghz (procesa muchos datos al tiemp ) vram
  tambien conectada a la ram
  mas efectiva procesamiento paralelizado

PERIFERICOS Y SISTEMAS DE ENTRADA DE INORMACION
Primer anillo - Kernel: El Kernel lo podemos entender como la capa mas profunda de nuestro S.O. por lo tanto tiene acceso completo a archivos, drivers, programas, etc…Igual que cualquier otro proceso, se carga en la RAM como la cualidad de que es lo primero en cargar.
En esta capa también viven programas capaces de encriptar y desencriptar información, de tal forma que ninguna otra capa del S.O. tenga acceso a ellos.
Segundo anillo - Drivers: Como se ha dicho antes los drivers son código que se encargan de interpretar las señales de el hardware y establecer una comunicación con el software del PC. Estos primeros drivers pertenecen a piezas de hardware bastante importantes como la pantalla, el teclado, el mouse, etc…
Es importante indicar que entre el primer y el segundo anillo hay un indice de permisos donde estan almacenados qué permisos tiene cada app
Tercer anillo - Mas Drivers: Otra capa de drivers carga en un tercer “puesto” en la RAM. Dado que están más alejados del Kernel, tienen menos permisos y privilegios que los drivers del segundo anillo. Dado que mediante los drivers de este anillo, se comunican en su mayoría las Apps, es necesario que primero los drivers del tercer anillo pidan permisos a los del segundo anillo para luego así comunicarse con el hardware.
Cuarto anillo - Apps: Finalmente en la última capa del modelo de anillos del S.O. nos encontramos con las apps, que se cargan en la RAM para ejecutar procesos. Sin embargo a diferencia de los otros anillos no tienen ningún tipo de acceso directo al hardware del PC. Es importante tener en cuenta que así debería ser, pues de lo contrario cualquier Software escrito por terceros tendría la capacidad de acceder casi por completo al PC y a sus piezas de Hardware.

Arquitectura de la computacion
  computadoras con trajetas fisicos huecos
  no existian estandares antes
  compus-laptop-celulares-raspberry-ardruino

Introduccion a las redes protocolos e internet
  Red local
    Pc
    Laptop
      Directamente con un calbe ethernet
      Switch
        Comparte la red con todos los conectados a los puertos
        Algoritmo pra enrutar datos
          pregunta a todos hasta encontrar a quien llega el mensaje
        Es ineficiente
        Celulares no tiene cable de red
      Router wifi
        se puede conectar al switch
        son inteligentes tienen una tabla de enrutameinto
          nombre de la red
          password
          iplist
        el asigna la ip con el dhcp
        recuerda pro caracteristicas de hardware
      Mac
        viene quemado dentro del computador
        numero uniko q identifica a cada computador (TODA ENTERFACE DE RED)
        Interfaz de red
          ethernet una mac addres
          wifi otra mac address
          radio otra mac address
      Modem
        al cual se conecta el router
        modem Isp
          adsl
          telefono (antiguo)
          lte
          fibra optica (mas optimo)
        
    Isp
    internet
    Cloud
    Twitter
