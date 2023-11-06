# Cabeceras H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Undelines
Underline 1
------------

Underline 2
===========


# Formatos de enfasis

-letra *italica* de la primera forma.


-letra _italica_ de la segunda forma.

Formato **bold o strong**.

Formato __bold o strong__.

formato tachado.


aqui podemos usar *italica* pero tambien **bold**

# Listas
1. Esto es un item.
2. Esto es un.
3. Esto es un.
- Esto es un item de listas desordenadas.
- Esto es un item de listas desordenadas.
- Esto es un item de listas desordenadas.
- Esto es un item de listas desordenadas.

# Links
- <a href = "https://www.google.com"> Es es un link HTML</a>
- [Esto es un link en Markdown](htt://www.google.com)
- [Esto es un link al index](index.html)


# Imagenes
![Logo GitHub](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/2560px-Git-logo.svg.png)

# Code Snippets
Codigo en Json
```JSON
{
  "status": "ok",
  "extended": true,
  "results": [
    {"value": 0, "type": "int64"},
    {"value": 1.0e+3, "type": "decimal"}
  ]
}
```

Codigo en Javascript
```Java
/**
 * @author John Smith <john.smith@example.com>
*/
package l2f.gameserver.model;

public abstract strictfp class L2Char extends L2Object {
  public static final Short ERROR = 0x0001;

  public void moveTo(int x, int y, int z) {
    _ai = null;
    log("Should not be called");
    if (1 > 5) { // wtf!?
      return;
    }
  }
```

# Tablas
| Nombre | Apellido | Documento
| ------- | -------- | --------
| Maxi    | Burgosz  |  356454
| -------- | ------- | --------

# Citas 
Esto es un texto referete a una cita que pondremos debajo.
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior.
> Esto es otra cita.

# Lineas divisorias.
Esto es un texto que sera dividido por giones medios. 

---
Esto es otro texto dividido por asteriscos.

***

Esto es otro texto dividido por guiones bajos.

___

# Saltos de lineas. 
Esto es nuestro primer parrafo.

Esto es nuestro SEGUNDO parrafo.

Esto es nuestro SEGUNDO parrafo.
- Lista