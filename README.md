# Tabla de contenido

1. [Plegar lineas](#plegar-lineas)
2. [Borrar y cambiar sentencia](#borrar-y-cambiar-sentencia)
3. [Manejo buffer](#manejo-buffer)
4. [Encerrar parentesis, llaves](vim-surround/readme.md)
5. [Movimientos](movimientos/readme.md)
6. [Eliminar](eliminar/readme.md)
7. [Copiar y pegar](copiar-pegar/readme.md)
8. [Buffer](buffer/readme.md)
9. [Comentarios](comentarios/readme.md)
10. [Remplazar texto](remplazar/readme.md)
11. [Buscar en todos los archivos](buscar/readme.md)

## Pensando VIM

![pensar vim](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/buw7fbof0run3iafirmk.png)

## Plegar lineas
Para plegar las lineas de codigo de mamnera manual, se debe configurar de la siguiente manera:

```
set nofoldenable
set foldmethod=manual
```

[Más información](https://vim.fandom.com/wiki/Folding)

| Comando | Descripción |
| :---: | :--- |
| `zf3j`| En modo **comando** puede plegar 3 lineas |
| `zf`| En modo **Visual** puede plegar el texto seleccionado |
| `zd`| Borra la marca de plegado |
| `zD`| Borra la marca de plegado recursivamente |

## Cambiar sentencia
Para cambiar una sentencia `cas`

## Manejo buffer

| comando | Descripción |
| :---: | :--- |
| `:ls` | Lista el actual buffer, incluyendo su número |
| `:b<numero>`| Abre el buffer con el número asignado |
| `:bd`| Borra el actual buffer |
| `Ctrl + o`| Se mueve al buffer abierto anteriormente |
| `Ctrl + i`| Mueve al proximo buffer |

