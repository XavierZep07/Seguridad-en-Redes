### Descripción 
Our server seems to be leaking pieces of a secret flag in its logs. The parts are scattered and sometimes repeated. Can you reconstruct the original flag?Download the [logs](https://challenge-files.picoctf.net/c_saffron_estate/3e417b56c25929c6c078813bba342ae27e2964223df8b72c4b67f65c876efa95/server.log) and figure out the full flag from the fragments.
### Soluciones
para resolver este problema solo tuve que leer el documento con los logs registrados, despues solo filtre los que tuvieran FLAGPART: en la linea, con eso encontre las partes de la bandera.

```
picoCTF{us3_y0urlinux_sk1lls_cedfa5fb}
```


### Notas adicionales 
utilice conocimientos previos

### Referencias 
