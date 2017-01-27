# templatesEclipseCDT

##Configuraciones

Para configurar que al momento de guardar un archivo java; eclipse idente, organice librerias ademas de otras acciones dirigirse a:

> Window > Prefereces > Java > Editor > Save Actions

Para que eclipse muestre en un codigo de colores las lineas donde se han realizado cambios desde la ultima sincronizacion del proyecto (**git/svn**) o incluso sin el uso de estas:

> Window > Prefereces > General > Editors > Text Editors > Quick Diff 

##Shortcuts

Para crear el Constructor con superclase, el Constructor con atributos y los Getter y Setter pocisionarse al final del documento y usar:

1. Alt + Shift + s > c
> Constructor con superclase

2. Alt + Shift + s > o
> Constructor con atributos

3. Alt + Shift + s > r
> Getter y Setter

Para abrir y cerrar el project explorer:

1. Ctrl + m

##Templates
Templates usados en eclipse por la CDT de la ESCOM, para agregarlos al workspace ir a:

> Window > Prefereces > Java > Editor > Templates > Import.

Para usarlos simplemente escribir el nombre de cada uno y utilizar autocompletar (**Alt +  Tab**).

* Java
 * Model
   * ColumnCDT
    * idColumnCDT
    * manyToOneCDT
    * nombreDescripcionColumnsCDT
    * oneToOneCDT
    * tableCDT
 * Ctrl
   * ResultSuccessCDT
