# Ejemplo de entrada y salida (datos inventados)

## Correo de entrada (cuerpo, ya convertido de HTML a texto)

```
VIN: WBA00000000X00000
Pieza causal: Panel de puerta delantera izquierda
Modo de fallo: Ruido / vibración
```
*(marca de tiempo del correo: 2026-03-14T09:42:00Z)*

## Fila resultante en Excel

| VIN               | Pieza causal                     | Modo de fallo      | Fecha            | ACABADO |
|-------------------|----------------------------------|--------------------|------------------|---------|
| WBA00000000X00000 | Panel de puerta delantera izq.   | Ruido / vibración  | 2026-03-14 10:42 | No      |

> Si llega un segundo aviso con el mismo VIN, el filtro `VIN eq '...'` lo detecta y **no** se añade
> una segunda fila. La fecha se guarda ya en hora local (una sola conversión desde UTC).
