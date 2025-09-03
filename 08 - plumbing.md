### Descripción 
Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to `jupiter.challenges.picoctf.org 14291`.

### Soluciones

Utilizando netcat como en el ejercicio anterior pude entrar al contenido de la pagina, despues de eso solo utilice un buscador como en un ejercicio anterior el cual era 

```
nc jupiter.challenges.picoctf.org 14291 | grep "pico"
```

esto solo para que me filtrara la linea donde estaba la respuesta


RESPUESTA

```
picoCTF{digital_plumb3r_ea8bfec7}
```


### Notas adicionales 

utilice conocimientos aprendidos en ejercicios anteriores

### Referencias 
