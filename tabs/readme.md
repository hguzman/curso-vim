# Manejo de tabs

Comando para manejar tabs en vim

## Navegación

```
:tabs         list all tabs including their displayed windows
:tabm 0       move current tab to first
:tabm         move current tab to last
:tabm {i}     move current tab to position i+1
:tabm +{i}    move current tab right to current position+i
:tabm -{i}    move current tab left to current position-i

:tabn         go to next tab
:tabp         go to previous tab
:tabfirst     go to first tab
:tablast      go to last tab
```

## En normal mode

```
gt            go to next tab
gT            go to previous tab
{i}gt         go to tab in position i
```
