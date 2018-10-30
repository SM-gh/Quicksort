---?color=linear-gradient(to top, #6dd5fa, #ffffff)
@title[Datos Generales]

@snap[split-screen-heading text-blue span-100]
Datos Generales
@snapend

+++?color=linear-gradient(to top, #0ed2f7, #20bdff, #a5fecb)
@title[Algoritmos de ordenamiento]

@snap[north-west text-white]
@size[0.7em](<br>**Es uno de los Algoritmos de ordenación**)
@snapend

@snap[north text-white span-100]
@size[0.6em](<br><br>Surgen de la necesidad de recuperar o buscar información de manera eficiente.)
@snapend

@snap[west text-white]
@size[0.6em](<br><br><br>**Tipos de ordenamiento:**)
@size[0.6em](<br>•**_Interno_**: La información cabe en la memoria principal de la computadora.)
@size[0.6em](<br>•_Externo_: Es necesario ocupar una memoria secundaria)
<br>
@size[0.6em](<br>**Clasificación de los algoritmos de ordenamiento:**)
@size[0.6em](<br>•	De _Selección_: En estos se selecciona el elemento mínimo o el máximo de todo el conjunto y se coloca en posición apropiada; esto se realiza con todos los elementos restantes)
@snapend

+++?color=linear-gradient(to top, #0ed2f7, #20bdff, #a5fecb)

@snap[north-east text-white span-100]
@size[0.6em](<br><br><br>-> Ejemplo: Inserción directa, Shell sort, inserción binaria, hashing.)
@size[0.6em](<br><br><br><br>->Ejemplo: Bubble sort y Quicksort.)
@snapend

<p align="justify">
@snap[west text-white]
@size[0.6em](•	De _inserción_: Se considera un elemento a la vez y cada elemento es insertado en la posición apropiada con respecto a los demás que ya han sido ordenados.<br><br>)
@size[0.6em](<br>•De **_intercambio_**: En estos se trabaja en parejas de elementos que se comparan e intercambian si no están en orden adecuado. Termina hasta que ya se hayan revisado todos los elementos.<br>)
@size[0.6em](<br>•	De _numeración_: Para estos se compara cada elemento con todos los demás y se determina cuántos son menores que él, así la información del conteo indicará su posición de ordenamiento.)
@snapend

</p>

+++?color=linear-gradient(to top, #0ed2f7, #20bdff, #a5fecb)

@snap[west text-white]
@size[0.6em](<br>Otras clasificaciones:)
@size[0.6em](<br>•	Métodos _iterativos_ vs **_Métodos recursivos_**:)
@size[0.6em](<br>•	De ordenación _natural_ vs _No natural_.)
@size[0.6em](<br>•	_Estables_ vs **_Inestables_**)
@snapend

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
