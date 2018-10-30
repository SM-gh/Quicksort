---?color=linear-gradient(to top, #2980b9, #6dd5fa, #ffffff)
@title[Datos Generales]

@snap[split-screen-heading text-blue span-50]
Datos<br>Generales
@snapend

+++?color=linear-gradient(to top, #fc00ff, #00dbde)
@title[Algoritmos de ordenamiento]

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

+++?color=linear-gradient(to top, #1e9600, #fff200, #ff0000)
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

@snap[split-screen-heading text-green span-50]
Ejemplo<br>Código
@snapend

+++?color=linear-gradient(to top, #00416a, #799f0c, #ffe000)
@title[Código]

---?color=linear-gradient(to left, #ee9ca7, #ffdde1)
@title[Rferencias]

@snap[east split-screen-heading text-pink span-50]
Referencias
@snapend
