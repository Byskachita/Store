# PASOS PARA EL DESPLIEGUE

1. Crear la máquina virtual en AWS

2. Habilitar en el grupo de seguridad los puerto 80 y 443

3. Personalizar los archivos de la carpeta *despliegue*

4. Copiar los archivos a la MV de AWS

5. Ejecutar el archivo *1_instalador_ruby.sh*

    ```bash
    # comando para ejecutar el archivo
    ./despliegue/1_instalador_ruby.sh
    ```

    ```bash
    # en caso de solicitud de permisos
    sudo chmod -R 777 despliegue
    ```

    ! Ejecutar comando `exec $SHELL` en caso de no haber instalado ruby
    
    Volver a ejecutar el archivo SIN reemplazar la llave ssh

6. Ejecutar el archivo *2_instalador_nginx_passenger.sh*

7. Ejecutar el archivo 

