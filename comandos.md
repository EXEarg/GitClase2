## crear un repositorio
    git init
> Este comando crea un repositorio en el directorio donde estamos situados.

## saber el estaod de cambios
    git status
>Este comando te informa qué archivos están en seguimiento.
>
>
>

## crear punto de restauración
    git commit -m 'msj'

## crear punto de restauración con título y descripción
    git -m 'título' -m 'descripción'
    
## agregar a staging area y crear punto de restauración
    git commit -am 'msj'

## ver listado completo de commits con su autor, descripción y timestamp
    git log
>se puede ver en forma corta, de una sola línea usando: git log --oneline
