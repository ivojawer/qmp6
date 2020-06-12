#QMP6

###Usuarios
En el momento de creacion (por ahora esto se resuelve con un constructor) estos se subcriben al generador de sugerencias y al servicio de alertas para ser notificados.
```
consturctor(){
    generadorSugerencias.subscribir(this)
    servicioAlertasMeteorologicas.subscribir(this)
}
```


