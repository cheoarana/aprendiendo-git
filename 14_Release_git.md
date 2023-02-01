# Release
![git-logo](images/git-logo.png)

## Ramas release

Esta rama es utilizada para un nuevo despliegue en el entorno productivo.

Esta rama depende de la rama **develop** para poder crearla
Cuando los cambios en develop hayan sido probados y certificados se crea la rama release.
Se fusiona con la rama main y despues se elimina

La convención del nombrado de ramas debe contener el versionamiento de tu desarrollo de software por ejemplo:

**release-0.1.2**