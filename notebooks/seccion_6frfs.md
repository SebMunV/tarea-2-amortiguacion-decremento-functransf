# 3.2 Las 6 Funciones de Respuesta en Frecuencia (FRFs)

Según **Tom Irvine (2000)**, existen **6 FRFs básicas** para un sistema SDOF, agrupadas en dos tablas según si la respuesta o la fuerza aparece en el numerador.

---

### Tabla 1 — Respuesta / Fuerza

| Nombre | También llamada | Relación | Unidad |
|---|---|---|---|
| **Receptancia** | Admitancia, Compliance | $X / F$ | m/N |
| **Movilidad** | — | $V / F = j\omega \cdot H(\omega)$ | (m/s)/N |
| **Acelerancia** | Inertance | $A / F = -\omega^2 \cdot H(\omega)$ | (m/s²)/N |

### Tabla 2 — Fuerza / Respuesta (inversas)

| Nombre | Relación | Unidad |
|---|---|---|
| **Rigidez Dinámica** | $F / X = 1 / H(\omega)$ | N/m |
| **Impedancia Mecánica** | $F / V = 1 / (j\omega \cdot H(\omega))$ | N·s/m |
| **Masa Aparente** | $F / A = -1 / (\omega^2 \cdot H(\omega))$ | kg |

---

> **Nota:** Todas las FRFs se derivan de la misma función base $H(\omega)$, multiplicando o dividiendo por potencias de $j\omega$. Donde las FRFs de la Tabla 1 tienen un **pico** en resonancia, las de la Tabla 2 tienen un **valle**.
