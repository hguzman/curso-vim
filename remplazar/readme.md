# Remplazar un texto

Muchas veces se requiere remplazar textos dentro de un archivo, el comando para realizarlo desde VIM es:

```
:%s/texto_a_sustituir/texto_nuevo/g

:6,10s/texto_a_sustituir/text_nuevo/gc
```

Tambien se puede hacer con el modo visual. `:'<,'>s/foo/bar/g`
