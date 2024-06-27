# Poli-NCR

## Pantalla Tactil

Guia para poder instalar los Drivers de la pantalla tactil Ubuntu.
- Copiar Tsharc304c.tar en el equipo
- Abrir la carpeta destino y abrir una terminal e ingresar el siguiente comando para descomprimir el archivo.
        
        - tar zxvf Tsharc304c.tar.gz
    
- Entrar en la carpeta descomprimida en la terminal e ingresar el siguiente comando.
        
        - sudo ./install.sh 

- Van a aparecer varias opciones en las cuales vamos a seleccionar la opcion 1 y posteriormente la opcion 12 para instalar los controladores
    
- Despues ingresar para configurar el inicio del driver cuando el sistema bootea
        
        - boot.tsharc start  
    
- Para poder configurar el driver tirar el siguiente comando
        
        - hlincal
    
- Va a salir un menú en donde vamos a calibrar el touch, para eso ingresar 3.
- Despues seleccionar la opcion 5 para poder calibrar la pantalla  
- ahí vamos a configurar el GUI, para eso ingresar 6    
- Despues se puede seguir cambiando la configuracion para amoldarlo mas a nuestros gustos.
- Y para terminar vamos a volver al menu anterior y si no queremos configurar nada mas se selecciona la opcion A para aplicar los cambios

Guia de la instalacion completa en: GuiaDeInstalacionCompletaLinux.pdf

## Lector de Tarjeta