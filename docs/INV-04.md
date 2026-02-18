# INV-04 Consultar producto

## Historia de usuario

**Como** administrador  
**Quiero** consultar productos por nombre o código  
**Para** encontrarlos rápidamente  

## Criterios de aceptación

**Escenario 1: Consulta exitosa**

Dado que existen productos registrados  
Cuando ingreso el nombre o código  
Entonces el sistema muestra el producto  

Y su información completa  

---

**Escenario 2: Producto no encontrado**

Dado que el producto no existe  
Cuando realizo la búsqueda  
Entonces el sistema informa que no existe
