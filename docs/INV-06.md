# INV-06 Registrar salida de stock

## Historia de usuario

**Como** administrador  
**Quiero** registrar salidas de stock  
**Para** llevar control de los productos  

## Criterios de aceptación

**Escenario 1: Registro correcto**

Dado que el producto existe  
Cuando registro una salida válida  
Entonces el sistema descuenta la cantidad  

Y actualiza el stock correctamente  

---

**Escenario 2: Stock insuficiente**

Dado que no hay suficiente stock  
Cuando intento registrar la salida  
Entonces el sistema muestra un mensaje de error
