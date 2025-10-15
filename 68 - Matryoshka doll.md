## Description
Matryoshka dolls are a set of wooden dolls of decreasing size placed one inside another. What's the final one? Image: [this](https://mercury.picoctf.net/static/5ef2e9103d55972d975437f68175b9ab/dolls.jpg)
### Solucion

```
picoCTF{e3f378fe6c1ea7f6bc5ac2c3d6801c1f}
```
### Notas Adicionales
para este ejercicio tuve que descomprimir la imagen dada por el problema para encontrar el archivo flag.txt que tenia la bandera

### Referencias

for i in {0..100}; do unzip *.jpg; cd base_images; done