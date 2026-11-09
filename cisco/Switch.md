# IOS Cisco

Proporcona comandos para verificar el funcionamiento de interfaces del enrutador y conmutador.

## Sintaxis
```bash
    Switch> show ip protocols
    # 0     1   2└──   3   --|
    # 0: Indicador
    # 1: Comando
    # 2: Espacio
    # 3: Palabra clave o argumento
```

### Teclas de Acceso rapido

| Pulsacion de Teclas | Descripcion |
| ---  | --- |
| Tab | Completa una entrada de nombre parcial |
| Ctrl +A | Desplaza el cursor al principio de la linea |
| Ctrl + K | Borra todos los caracteres desde el cursor hacia la derecha |
| Ctrl + E | Desplaza el cursor hacia el final de la linea |
| Ctrl + D | Borra el caracter donde esta el cursor |
| Flecha arriba | recupera el comando anterior del buffer del hisorial |
| Ctrl + C | Ctrl + z + cuando esta en modo de configuracion interrumpe y regresa al simbolo del sistema |
| CTRL + Z | Sale del modo de configuracion, termina el modo de configuracion y regresa como usuario EXEC Privilegiado |
| Ctrl + Shift + 6 | Secuencia de interrupcion multiproposito (cancelar un ping, busquedas DNS y para interrumpir procesos de IOS) |
| espacio | muestra la siguiente pantalla |
| exit | vuelve a un nivel anterior | 

- ***show***: Muestran informacion sobre la configuracion y el funcionamiento del dispositivo.
    ```bash
    # Muestra la configuracion y ajustes actuales.
    show running-config 

    # Muestra el estado de todas las interfaces y mensajes de error.
    show interfaces 

    # Verifica la informacion de capa 3 de la interfaz
    show ip interface

    # Muestra los hosts conectados de la tabla ARP.
    show arp
    
    # Verifica enrutamiento
    show ip route

    # Muestra que protocolos estan operativos.
    show protocols

    # Version de IOS
    show version
    ```