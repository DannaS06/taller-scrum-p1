# INV-03 Eliminar producto

## Historia de usuario

**Como** administrador  
**Quiero** eliminar productos descontinuados  
**Para** mantener limpio el sistema  

## Criterios de aceptación

**Escenario 1: Eliminación correcta**

Dado que el producto existe en el inventario  
Cuando selecciono la opción eliminar producto  
Y confirmo la eliminación  
Entonces el sistema elimina el producto correctamente  

Y el producto ya no aparece en la lista  

---

**Escenario 2: Cancelación**

Dado que selecciono eliminar producto  
Cuando cancelo la operación  
Entonces el producto permanece en el sistema
