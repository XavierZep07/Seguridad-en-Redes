### Descripción 
There's an interesting script in the user's home directoryThe work computer is running SSH. We've been given a script which performs some basic calculations, explore the script and find a flag.

Hostname: saturn.picoctf.net 
Port:52958 
Username: picoplayer Password: password


### Soluciones
primero utilizo ssh para poder correr la linea que daba el problema esto con los datos que me daba la instancia
```
PakoMarrano-picoctf@webshell:~$ ssh picoplayer@saturn.picoctf.net -p 52958
```
 
despues solo escribi la contraseña y pude entrara, despues solo abri el documento con cat y me dio la bandera que buscaba 


RESPUESTA

```
picoCTF{us3l3ss_ch4ll3ng3_3xpl0it3d_6140}
```


### Notas adicionales 

utilice conocimientos aprendidos en ejercicios anteriores

### Referencias 
