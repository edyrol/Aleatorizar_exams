# Aleatorizar exámenes

Crea exámenes aleatorios a partir de un archivo tex.

El formato es `aleatoriza(filename,num_exams,separator)`.

`filename` es un archivo tex. Debe contener algo como `\newcommand{\numa}{xxxa} %option1,option2`. Lo que hace es identifica la palabra (de 4 letras) que empieza con `xxx` y la reemplaza aleatoriamente con una de las opciones comentadas de ese renglón. Hay que tener cuidado de que el texto no contenga la palabra `xxx` en otros lados.

`num_exams` es el número de examenes que se generarán, puede que salgan repetidos.

`separator` es el símbolo con el que se separan las opciones en los comentarios. Es una coma por defecto.

Se imprimen las posibles sustituciones para evitar errores. Compila los archivos y deja únicamente los pdf.
