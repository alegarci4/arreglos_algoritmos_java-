\# Parte 2 – Ejercicio Algoritmico 



Inicio



Leer arreglo A



Si tamaño de A < 2 entonces

    Mostrar "No se puede calcular"

    Terminar

Fin Si



mayor = -∞

segundoMayor = -∞

menor = +∞

segundoMenor = +∞



Para cada elemento num en A hacer



    // Evaluar mayor y segundo mayor



    Si num > mayor entonces

        segundoMayor = mayor

        mayor = num

    Sino si num > segundoMayor Y num != mayor entonces

        segundoMayor = num

    Fin Si







    // Evaluar menor y segundo menor



    Si num < menor entonces

        segundoMenor = menor

        menor = num

    Sino si num < segundoMenor Y num != menor entonces

        segundoMenor = num

    Fin Si



Fin Para



Mostrar segundoMayor

Mostrar segundoMenor



Fin



\##EXPLICACIÓN BREVE:

El algoritmo funciona porque mantiene actualizadas cuatro variables durante un único recorrido, cada vez que se encuentra un nuevo      valor más grande o más pequeño, se actualizan las variables asi no es necesario recorrer el arreglo mas veces.

\##COMPLEJIDAD TIEMPO:

&nbsp;O(n) Porque el arreglo se recorre una sola vez

\##COMPLEJIDAD ESPACIO: 

O(1) Porque solo se utilizan cuatro variables sin importar el tamaño del arreglo.

