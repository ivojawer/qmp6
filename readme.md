# QMP6

### Usuarios
En el momento de creacion (por ahora esto se resuelve con un constructor) el usuario se subscribe al servicio de alertas para ser notificados.
```
consturctor(servicioAlertasMeteorologicas: AlertadorMeteorologico){
    servicioAlertasMeteorologicas.subscribir(this)
}
```
Para que sea llamado el metodo `recibirAlerta`
