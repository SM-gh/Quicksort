---?color=linear-gradient(to top, #6dd5fa, #ffffff)
@title[Datos Generales]

@snap[split-screen-heading text-blue span-100]
Datos Generales
@snapend

+++?color=linear-gradient(to top, #0ed2f7, #20bdff, #a5fecb)
@title[Algoritmos de ordenamiento]

@size[0.6em](Es uno de los Algoritmos de ordenación<br>Surgen de la necesidad de recuperar o buscar información de manera eficiente.)

@size[0.6em](Tipos de ordenamiento:
<br>•Interno: La información cabe en la memoria principal de la computadora.
<br>•Externo: Es necesario ocupar una memoria secundaria)

@size[0.6em](Clasificación de los algoritmos de ordenamiento:
<br>•	De inserción: Se considera un elemento a la vez y cada elemento es insertado en la posición apropiada con respecto a los demás que ya han sido ordenados.
<br>->	Ejemplo: Inserción directa, Shell sort, inserción binaria, hashing.
<br>•	De intercambio: En estos se trabaja en parejas de elementos que se comparan e intercambian si no están en orden adecuado. Termina hasta que ya se hayan revisado todos los elementos.
<br>->Ejemplo: Bubble sort y Quicksort.
<br>•	De Selección: En estos se selecciona el elemento mínimo o el máximo de todo el conjunto y se coloca en posición apropiada; esto se realiza con todos los elementos restantes
<br>•	De numeración: Para estos se compara cada elemento con todos los demás y se determina cuántos son menores que él, así la información del conteo indicará su posición de ordenamiento.)

@size[0.6em](Otras clasificaciones:
<br>•	Métodos iterativos vs Métodos recursivos:
<br>•	De ordenación natural vs No natural.
<br>•	Estables vs Inestables)

+++?color=linear-gradient(to top, #ef32d9, #00dbde, #89fffd )

 #### @color[#ffff](Creado por el britáino científico en computación<br>Charles Antony Richard Hoare)

<p align="center">
  <img width="270" height="370" src="https://github.com/SM-gh/Quicksort/blob/master/template/img/CARHoare.png?raw=true">
</p>

+++?color=linear-gradient(to top, #12c2e9, #c471ed, #ee9ca7, #b2fefa)

Sigue el pensamiento “divide y vencerás”

---?color=linear-gradient(to left, #fceabb, #f8b500)
@title[Algoritmo]

@snap[east split-screen-heading text-orange span-50]
Algoritmo
@snapend 

@snap[west text-white span-50]
@ol[split-screen-list](false)
- Se elige un elemento de la lista (pivote).
- Resituar los demás elementos a cada lado del pivote (a un lado mayores y al otro menores) <sup>1</sup>.
- Repetir recursivamente para cada sublista <sup>2</sup>.
@olend
@snapend

@snap[south-west template-note text-white]
<sup>1</sup> La  orientación de todos los elementos y de los iguales al pivote dependen de la  implementación deseada.<br>
<sup>2</sup> Debe  de contener mas de un elemento.
@snapend

+++?color=linear-gradient(to top, #ff5f6d, #fe8c00, #f9d423, #fffc00, #fdfc47)
@title[Eficiencia]

@snap[north]
@fa[arrow-right text-white]@color[white](EFICIENCIA)
@snapend

@snap[west text-white]
@size[0.8em](Depende de la posición en la que termine el pivote elegido:)<br>
<br>•@size[0.7em](En el MEJOR CASO, termina en el CENTRO de la lista, dividiéndola en dos sublistas de igual tamaño.<br>-> Orden de complejidad del algoritmo: O(n·log n))<br>
<br>•@size[0.7em](En el PEOR CASO, el pivote termina EN UN EXTREMO de la lista.<sup>1</sup><br>-> Orden de complejidad del algoritmo: O(n²))
@snapend
  
@snap[south-west template-note text-white]
<sup>1</sup> Depende de la implementación del algoritmo, aunque habitualmente ocurre en listas ordenadas, o casi ordenadas y principalmente depende del pivote.<br>
@snapend

---?color=linear-gradient(to top, #a1ffce, #faffd1)
@title[Código ejemplo]

@snap[split-screen-heading text-green span-100]
Ejemplo Código
@snapend

+++?color=linear-gradient(to bottom, #a8ff78, #78ffd6)

---?color=linear-gradient(to left, #ee9ca7, #ffdde1, #ffff)
@title[Rferencias]

@snap[west split-screen-heading text-pink span-50]
Referencias
@snapend
