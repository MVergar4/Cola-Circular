# Cola-Circular

Para compilar ejecutar el siguiente comando en la terminal:
gcc -o cola colacircular.c

Luego, si compila bien, se ejecuta con el siguiente comando en la terminal:
./cola -p <número de productores> -c <número de consumidores> -s <tamaño inicial de cola> -t <tiempo de espera máxima de consumidores en segundos>

El progreso de la ejecución del programa se guarda en un archivo log llamado "ejecucion.log".
La primera vez que se ejecuta el programa este archivo se crea, si dicho archivo ya existe, entonces se sobrescribe con la ejecución más reciente.
