---?color=linear-gradient(to top, #6dd5fa, #ffffff)
@title[Datos Generales]

@snap[split-screen-heading text-blue span-100]
Datos Generales
@snapend

+++?color=linear-gradient(to top, #0ed2f7, #20bdff, #a5fecb)
@title[Algoritmos de ordenamiento]

@snap[north-west]
<br>@fa[arrow-right text-white]@color[white](@size[1.0em](**Es uno de los Algoritmos de ordenación**))
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
@size[0.6em](<br><br><br><br>-> Ejemplo: Bubble sort y Quicksort.)
@snapend

<p align="justify">
@snap[west text-white]
@size[0.6em](•	De _inserción_: Se considera un elemento a la vez y cada elemento es insertado en la posición apropiada con respecto a los demás que ya han sido ordenados.<br><br>)
@size[0.6em](<br>•De **_intercambio_**: En estos se trabaja en parejas de elementos que se comparan e intercambian si no están en orden adecuado. Termina hasta que ya se hayan revisado todos los elementos.<br>)
@size[0.6em](<br>•	De _numeración_: Para estos se compara cada elemento con todos los demás y se determina cuántos son menores que él, así la información del conteo indicará su posición de ordenamiento.)
@snapend
</p>

+++?color=linear-gradient(to top, #0ed2f7, #20bdff, #a5fecb)

@snap[north-west text-white]
@size[0.6em](<br>Otras clasificaciones:)
@size[0.6em](<br>•	Métodos _iterativos_ vs **_Métodos recursivos_**:)
@size[0.6em](<br>•	De ordenación _natural_ vs _No natural_.)
@size[0.6em](<br>•	_Estables_ vs **_Inestables_**)
@snapend

@snap[south-east]
<p align="center">
  <img width="680" height="350" src="https://pythonizame.s3.amazonaws.com/media/uploads/2015/11/04/fq0a8hx.gif">
</p>
@snapend

+++?color=linear-gradient(to top, #ef32d9, #00dbde, #89fffd )

@snap[north text-white span-100]
@fa[arrow-right text-white]@size[1.0em](@color[white](**Creado por el britáino científico en computación<br>Charles Antony Richard Hoare**))

@snapend

<p align="center">
  <img width="270" height="370" src="https://github.com/SM-gh/Quicksort/blob/master/template/img/CARHoare.png?raw=true">
</p>

@snap[south text-white span-100]
@size[0.7em](Sigue el pensamiento: “divide y vencerás”)
@snapend

+++?color=linear-gradient(to top, #12c2e9, #c471ed, #ee9ca7, #b2fefa)

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

+++?color=linear-gradient(to top, #ff5f6d, #fe8c00, #f9d423, #fffc00)
@title[Eficiencia]

@snap[north]
@fa[arrow-right text-white]@color[white](**EFICIENCIA**)
@snapend

@snap[north-west text-white]
<br><br>
@size[0.6em](Depende de la posición en la que termine el pivote elegido:)<br>
<br>•@size[0.6em](En el _mejor caso_, termina en el _centro_ de la lista, dividiéndola en dos sublistas de igual tamaño.<br><br>)
<br>•@size[0.6em](En el _peor caso_, el pivote termina _en un extremo_ de la lista.<sup>1</sup><br>)
@snapend

@snap[north-east text-white span-100]
@size[0.6em](<br><br><br><br><br><br>-> Orden de complejidad del algoritmo: O(n·log(n)) )
@size[0.6em](<br><br><br>-> Orden de complejidad del algoritmo: O(n²) )
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
<p align="center">
  <img width="500" height="600" src="https://user-images.githubusercontent.com/38449287/47753695-10b2f400-dc5e-11e8-80ff-da2cdc160bf5.JPG">
</p>

+++?color=linear-gradient(to bottom, #a8ff78, #78ffd6)
<p align="center">
  <img width="450" height="600" src="https://user-images.githubusercontent.com/38449287/47753729-27f1e180-dc5e-11e8-9fcb-66194583b6e1.JPG">
</p>

---?color=linear-gradient(to left, #ee9ca7, #ffdde1, #ffff)
@title[Rferencias]

@snap[west split-screen-heading text-pink span-50]
Referencias
@snapend

@snap[north-east]
Quicksort:
[Quicksort-Animaciones](http://lwh.free.fr/pages/algo/tri/tri_rapide_es.html)
Algoritmos de ordenamiento:
[Manual de prácticas UNAM](http://odin.fi-b.unam.mx/salac/practicasEDAII/MADO-20_EDAII.pdf)
Github+GitPitch:
[Generalidades GitPitch](https://gitpitch.com/docs)
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#links)
@snapend
