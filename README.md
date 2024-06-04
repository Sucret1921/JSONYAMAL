# GUÍA SOBRE JSON Y YAML

**ÍNDICE**   
1. [YAML](#id1)
2. [JSON](#id2)


## YAML<a name="id1"></a>

YAML (YAML Ain't Markup Language) es un formato de texto pensado para la serialización de datos, propuesto como alternativa a XML. Su sintaxis combina conceptos de varios lenguajes (HTML, C, Perl y Python).

El formato YAML fue propuesto por Clark Evans a principios de 2001 y dado a conocer a través de su página web http://yaml.org/.

El formato YAML no se ha publicado como norma por ningún organismo de normalización.
 
Las tres versiones publicadas:

   - enero de 2004: YAML 1.0
   - diciembre de 2004: YAML 1.1
   - octubre de 2009: YAML 1.2

![YAML IMAGEN](https://uxwing.com/wp-content/themes/uxwing/download/file-and-folder-type/yaml-file-icon.png)






## JSON<a name="id2"></a>

JavaScript Object Notation (JSON) es el formato de intercambio de datos que lo hace posible. JSON se ha convertido en un formato de datos popular para los 
desarrolladores debido a su texto legible por humanos, que es ligero, requiere menos codificación y se procesa más rápido al no requerir deserialización.


![imagen](https://github.com/Sucret1921/JSONYAMAL/assets/153021297/664dda6b-0760-40a1-8721-3130db03356c)

Las reglas sintáctica de JSON son bastante sencillas:

   - En JSON existen dos tipos de elementos
     - matrices (arrays): Las matrices son listas de valores separados por comas. Las matrices se escriben entre corchetes [ ] 
   - Objetos (objects). Los objetos son listas de parejas nombre / valor. El nombre y el valor están separados por dos puntos :
         y las parejas estánseparadaspor comas. 
     - Los objetos se escriben entre llaves {} y los nombres de las parejas se escriben siempre entre comillas dobles. 
   - Los espacios en blanco y los saltos de línea no son significativos, es decir, puede haber cualquier número
       de espacios en blanco o saltos de línea separando 
       cualquier elemento o símbolo del documento

Ejemplos prácticos de los puntos anteriores: 

```
[1, "pepe", 3.14, "Pepito Conejo"] 
```
```
{"nombre": "Pepito Conejo", "edad": 25, "carnet de conducir": true}
```
    
```
 [
  {
    "nombre": "Pepito Conejo",
    "edad": 25,
    "carnet de conducir": true
  },
  {
    "nombre": "Ana Barberá",
    "edad": 90,
    "carnet de conducir": false
  }
  ]
```
