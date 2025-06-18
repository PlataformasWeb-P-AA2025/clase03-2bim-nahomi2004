# clase03-2bim

Cuando no existe en la clase que contiene la foreing key un `related_name` para llamar a esa lista de atributos asociados se debe usar `e.[nombre de la clase en minusculas]_set.all` en vez de `e.[related_name].all`
![Set all](setall.png)
