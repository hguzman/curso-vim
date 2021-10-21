# Eliminar ó borrar

| Comando | Hablemos vim | descripción |
| --- | --- | --- |
| `das` | **d**elete **a**rount **s**entense | Borra alrededor de la sentencia |
| `diw` | **d**elete **i**side **w**ord | Borra plabra donde esta el cursor |
| `dw` | **d**elete **w**ord | Borra desde el cursor hasta el final de la palabra incluyendo espacio |
| `D` | **D**elete | Borra desde el cursor hasta el final de la linea |
| `d0` | **d**elete 0 | Borra desde el cursor hasta el inicio de la linea |
| `dG` | **d**elete G | Borra desde la linea actual hasta el final del archivo |

# Eliminar todas las filas en blanco de un archivo

`:g/^$/d`
