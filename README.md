Noé Isaí Hernández Rivas / SMSS010623
Eduardo Antonio Fuentes Melara

a. Describe brevemente de qué trata el dataset utilizado
El dataset que usamos contiene estadísticas de los "Stands", que son habilidades sobrenaturales de los personajes en el anime y manga JoJo’s Bizarre Adventure. Cada Stand tiene valores asignados a diferentes atributos como poder, velocidad, precisión, rango, durabilidad y potencial de desarrollo. Estos atributos están calificados del 1 al 10 o con letras tipo A, B, C, dependiendo del Stand.

b. ¿Qué información permite ver el resumen estadístico?
El resumen estadístico generado con describe() nos muestra valores como la media, la mediana, el valor mínimo y máximo, así como la desviación estándar de las columnas numéricas del dataset. Esto nos da una idea general de cómo están distribuidos los datos y si hay Stands con valores muy altos o bajos en ciertos atributos.

c. ¿Qué cambios o tendencias se detectan en la información del dataset?
Al observar los primeros y últimos registros y al ordenar por atributos como "Power", se pueden notar tendencias como qué tipos de Stands suelen tener valores más altos en atributos clave. Por ejemplo, varios Stands más famosos o de protagonistas tienden a tener estadísticas elevadas en fuerza y durabilidad.

d. ¿Qué categorías sobresalen en la comparación y por qué crees que será?
Las categorías como "Power" y "Speed" sobresalen bastante. Los Stands con valores altos en estos atributos generalmente pertenecen a personajes principales, lo que tiene sentido porque suelen ser los más poderosos dentro de la historia. Esto probablemente se deba a decisiones narrativas del autor para hacerlos destacar.

e. ¿Qué diferencias se observan entre los primeros y últimos registros?
Los primeros registros (con head()) muestran Stands con valores más equilibrados o bajos, mientras que los últimos (tail()) incluyen algunos con atributos extremos o incluso faltantes. Esto podría deberse al orden del archivo, o a que los últimos registros incluyen Stands menos conocidos o más experimentales.

f. ¿Qué aportan las medidas estadísticas al análisis del dataset?
Las medidas como la media, mediana y desviación estándar nos ayudan a entender cómo se comportan los datos en general. Por ejemplo, si la media de "Power" es muy alta pero hay una desviación estándar grande, quiere decir que hay mucha variedad entre Stands débiles y fuertes. Esto nos permite hacer comparaciones más objetivas y no solo guiarnos por la percepción que tenemos de los personajes.
