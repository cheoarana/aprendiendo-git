# Más sobre Git

![git-logo](images/git-logo.png)

## ¿Qué es el directorio de trabajo?

Es la carpeta contenedora de los ficheros de tu proyecto, en el cual has iniciado el repositorio

## ¿Qué es el área de staging?

Es un área temporal, donde es posible mover los archivos **modificados** del directorio de trabajo al estado **preparado**.

El comando utilizado es:
```
git add
```

## ¿Qué es un commit?
Un commit es la confirmación y guardado de los cambios hechos en el repositorio, es fundamental para entender como funciona Git

El comando utilizado es:

```
git commit -m "message"
```

Es muy importante entender que cada **commit** , es una imagen completa de tu repositorio.
Un commit tiene los siguientes datos entre otros:
* Autor
* Fecha
* Mensaje de commit
* Identificador de commit
