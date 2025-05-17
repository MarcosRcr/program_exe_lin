# Reach - Descarga

Este repositorio contiene dos archivos ejecutables para diferentes sistemas operativos:

- **reach**: Para sistemas Linux.
- **reach.exe**: Para sistemas Windows.

## Instrucciones de descarga

1. Haz clic en el archivo que corresponda a tu sistema operativo:

   - [reach](./reach) (Linux)
   - [reach.exe](./reach.exe) (Windows)

2. Descarga el archivo a tu computadora.

### Para usuarios de Linux

Después de descargar el archivo `reach`, dale permisos de ejecución con el siguiente comando:

```bash
chmod +x reach
```

Si deseas poder ejecutar `reach` desde cualquier lugar, mueve el archivo a un directorio incluido en tu variable `PATH`, por ejemplo:

```bash
sudo mv reach /usr/local/bin/
```

Luego puedes ejecutarlo con:

```bash
./reach
```

### Para usuarios de Windows

Simplemente haz doble clic en `reach.exe` para ejecutarlo.

Si deseas ejecutarlo desde cualquier ubicación en la terminal, agrega la carpeta donde guardaste `reach.exe` a las variables de entorno del sistema (`PATH`). Para hacerlo:

1. Haz clic derecho en "Este equipo" y selecciona "Propiedades".
2. Ve a "Configuración avanzada del sistema".
3. Haz clic en "Variables de entorno".
4. En "Variables del sistema", busca y selecciona la variable `Path`, luego haz clic en "Editar".
5. Agrega la ruta de la carpeta donde está `reach.exe` y guarda los cambios.
