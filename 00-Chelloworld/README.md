# TPO- Hello world!
## Compilador
- Utilicé el compilador GCC del entorno de [mingw64](https://www.mingw-w64.org/)
- La versión del compilador 11.2.0 es compatible con el estandar C11.

## Instrucciones de compilación
- Instalar el mingw64 siguiendo el link anexado
- Una vez instalado configurar el compilador dentro de la variable de entorno "Path"
    - Buscar la ruta de Mingw64 que contiene a la carpeta "bin"
    - Copiar la ruta
    - Buscar las variables de entorno y agregar una nueva con la ruta ya copiada dentro de la carpeta path
    - Abrir la terminal de tu preferencia (CMD, Powershell)
    - Verificar que la instalación haya sido correcta utilizando el comando "gcc --version"
    - Si tu terminal te muestra la versión del compilador instalado ya estas listo para correr tu primer código en C. En el caso contrario verificar los pasos realizados.
    - Uno de los errores más frecuentes se puede dar en no configurar de manera correcta las variables de entorno, si crees que este es tu caso intenta siguiendo los [siguientes pasos](https://docs.google.com/document/d/1kbxk375dZ8-27tqXAl_KvWpHVc9KsaOr0KB17aK-lhM/edit?usp=sharing)