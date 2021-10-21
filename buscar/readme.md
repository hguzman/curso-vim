# Buscar en VIM

## Buscar en todos los archivos

If you want search form a word in vim, you can use vimgrep.

```
:vimgrep /header/g **/*.rb
```

After that you can open the quick list `:copen`

To open the quickfix window in a horizontal rather than vertical split do `:vert copen`.

## buscar dentro del archivo

se puede usar `/<ctrl+r><ctrl+w>` para realizar una busqueda de la palabra que esta sobre el cursor
