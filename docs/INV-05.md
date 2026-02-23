# INV-05 Registrar entrada de stock

## Historia de usuario

**Como** administrador  
**Quiero** registrar entradas de stock  
**Para** actualizar las cantidades disponibles  

## Criterios de aceptación

**Escenario 1: Registro correcto**

Dado que el producto existe  
Cuando registro una entrada con datos válidos  
Entonces el sistema actualiza el stock correctamente  

Y aumenta la cantidad disponible  

---

**Escenario 2: Datos inválidos**

Dado que ingreso datos incorrectos  
Cuando intento registrar la entrada  
Entonces el sistema muestra un mensaje de error
