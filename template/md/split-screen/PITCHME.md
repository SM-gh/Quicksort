---?image=template/img/bg/CoolSky.jpg&position=right&size=100%
@title[Datos Generales]

@snap[west split-screen-heading text-blue span-50]
Datos<br>Generales
@snapend

@snap[east text-white span-65]
@ol[split-screen-list](false)
- Algoritmo de ordenación.
- Creado por el científico en computación C.A.R. Hoare.
- Sigue el pensamiento “divide y vencerás”.
@olend
@snapend

+++?color=linear-gradient(to top, #fc00ff, #00dbde)

---?image=template/img/bg/SunOnTheHorizon.jpg

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

@snap[north-west]
@fa[arrow-right text-white] @color[white](EFICIENCIA)
@snapend

@snap[west list-content-verbose span-120]
@size[0.8em](Depende de la posición en la que termine el pivote elegido:)
@ul[text-white](false)
- @size[0.8em](En el MEJOR CASO, termina en el CENTRO de la lista, dividiéndola en dos sublistas de igual tamaño.)
- @size[0.8em](El orden de complejidad del algoritmo es O(n·log n).)
- @size[0.8em](En el PEOR CASO, el pivote termina EN UN EXTREMO de la lista.)
- @size[0.8em](El orden de complejidad del algoritmo es entonces de O(n²).)
- @size[0.8em](Depende de la implementación del algoritmo, aunque habitualmente ocurre en listas ordenadas, o casi ordenada y principalmente depende del pivote. (si por ejemplo el algoritmo  toma como pivote siempre el primer elemento del array, y el array que le pasamos está ordenado, siempre va a generar a su izquierda un array vacío).)
@ulend
@snapend

---?image=template/img/bg/Limeade.jpg

@snap[west split-screen-heading text-green span-50]
Ejemplo<br>Código
@snapend

+++?color=linear-gradient(to top, #00416a, #799f0c, #ffe000)

---?image=template/img/bg/Piglet.jpg&position

@snap[east split-screen-heading text-pink span-50]
Referencias
@snapend
