# INV-07 Alertas de stock bajo

## Historia de usuario

**Como** administrador  
**Quiero** recibir alertas cuando el stock sea bajo  
**Para** evitar desabastecimiento  

## Criterios de aceptación

**Escenario 1: Generación de alerta**

Dado que el stock está por debajo del mínimo  
Cuando el sistema lo detecta  
Entonces muestra una alerta  

---

**Escenario 2: Stock suficiente**

Dado que el stock es suficiente  
Cuando reviso el inventario  
Entonces el sistema no muestra alertas
