# Mejoras para la app **workdextractor.py**

Para el estudiante más aventurero, aquí hay una lista de ideas para ampliar aún más la herramienta:

- Agregue un argumento `--output/` -oque nos permita definir un archivo de salida para imprimir en lugar de la consola (algo como **with open('path.txt', 'w') as wr:y wr.write(word)**).
- Agregue mutaciones de contraseña comunes a la salida, por ejemplo, en mayúsculas, minúsculas, MAYÚSCULAS y con varios bits agregados como los años actuales y recientes, números o símbolos aleatorios, por ejemplo, 2019, 1!, 2!, 3!, 01, 123. **Summer2021**!y variaciones similares son contraseñas deprimentemente frecuentes.
- Agregue un argumento `--depth/` que especifique la profundidad de rastreo del script. Esto implica la capacidad de capturar no sólo palabras sino también URL en las páginas web, verificar si están dentro del alcance (por ejemplo, dominio) y agregarlas a una lista de páginas para rastrear a continuación.`-d`
- Actualmente, el programa falla si se especifica una longitud mínima de 10 o más. Intente descubrir por qué y solucionarlo (pista: consulte el último bucle for).