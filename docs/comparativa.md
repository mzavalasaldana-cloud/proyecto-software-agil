# Comparativa de Metodologías y Estudio de Casos

> Entregables 1 y 2 de la Guía de Laboratorio Nº 01.

---

## 1. Cuadro comparativo: tradicionales vs. ágiles

| Criterio | Metodologías tradicionales (Cascada) | Metodologías ágiles (Scrum) |
|---|---|---|
| **Enfoque** | Predictivo y secuencial: se planifica todo el proyecto por adelantado y se ejecuta según el plan. | Adaptativo, iterativo e incremental: se planifica en detalle solo el ciclo próximo. |
| **Manejo de requisitos** | Se congelan al inicio; todo cambio pasa por un control formal y suele encarecer el proyecto. | Se aceptan y se aprovechan; el Backlog se reordena en cada ciclo según prioridad. |
| **Ciclo de vida** | Fases únicas y consecutivas: Análisis → Diseño → Codificación → Pruebas → Implantación. | Sprints cortos de 1 a 4 semanas; cada Sprint repite el ciclo completo sobre un subconjunto del alcance. |
| **Entrega** | Una sola entrega, al final del proyecto. | Entrega continua: un incremento de software funcionando al final de cada Sprint. |
| **Documentación** | Exhaustiva y previa; es el principal artefacto de control y de traspaso. | La necesaria y suficiente; el software funcionando es la evidencia principal de avance. |
| **Rol del cliente** | Participa al inicio (levantamiento) y al final (aceptación); poco involucrado durante el desarrollo. | Colabora de forma continua: prioriza el Backlog y valida cada incremento. |
| **Gestión del riesgo** | El riesgo se concentra al final: los errores de interpretación aparecen en la entrega. | El riesgo se distribuye: cada Sprint valida supuestos y corrige desviaciones temprano. |
| **Ventajas** | Estructura clara, avance medible por fases, costo y plazo estimables desde el inicio, fácil de auditar. | Adaptación rápida al cambio, valor entregado temprano, retroalimentación real, menor riesgo acumulado. |
| **Desventajas** | Rígida ante el cambio, el valor llega solo al final, alto costo de corrección tardía. | Menor previsibilidad de alcance y costo total, exige disciplina del equipo y disponibilidad real del cliente. |

---

## 2. Estudio de 3 casos y justificación metodológica

### Caso 1 — Sistema de inventarios estable

**Características:** requisitos definidos y conocidos desde el inicio, alcance estable, funcionalidad ampliamente probada en el mercado, usuarios y procesos ya establecidos.

**Metodología recomendada:** Cascada (tradicional).

**Justificación:** cuando los requisitos no van a evolucionar, la principal ventaja del enfoque ágil —adaptarse al cambio— no aporta valor, mientras que su costo de coordinación (ceremonias, replanificación continua) sí se paga. Un dominio conocido permite estimar el esfuerzo con precisión desde el inicio y planificar las fases de forma secuencial. Aquí la previsibilidad de plazo y costo es más valiosa que la flexibilidad.

**Por qué no ágil:** generaría una sobrecarga de reuniones e iteraciones sin beneficio adaptativo, porque el alcance no cambia.

---

### Caso 2 — Plataforma de comercio electrónico en evolución

**Características:** mercado cambiante, presión competitiva, requisitos que surgen de la retroalimentación de clientes y de métricas de uso, incorporación continua de funcionalidades (pagos, promociones, integraciones, reportes).

**Metodología recomendada:** Scrum (ágil).

**Justificación:** el producto se descubre mientras se construye. Se necesita entregar valor incrementalmente cada 1–2 semanas, medir el comportamiento real de los usuarios y reordenar prioridades con esa evidencia. La previsibilidad a largo plazo es baja, así que planificar doce meses por adelantado sería planificar sobre supuestos que caducan. El enfoque iterativo convierte el cambio en ventaja competitiva en lugar de en desvío del plan.

**Por qué no cascada:** al terminar el desarrollo completo, el producto ya respondería a un mercado que cambió; el costo de reabrir la planificación por cada cambio sería prohibitivo.

---

### Caso 3 — Software médico regulado

**Características:** normativas sanitarias estrictas, documentación y trazabilidad obligatorias, validaciones y certificaciones externas, alto impacto de un fallo sobre la seguridad del paciente.

**Metodología recomendada:** enfoque híbrido — marco tradicional con desarrollo interno iterativo.

**Justificación:** los requisitos regulatorios son fijos, están definidos por un tercero y no se negocian sobre la marcha; exigen especificación previa, trazabilidad requisito–diseño–prueba y evidencia documental completa. Ese marco es incompatible con "descubrir el alcance en el camino". Sin embargo, dentro de cada fase el equipo sí puede trabajar de forma incremental: construir y verificar módulo por módulo, con integración y pruebas continuas, siempre que cada incremento quede documentado y trazado. Así se gana calidad técnica sin comprometer el cumplimiento normativo.

**Por qué no puramente ágil:** la documentación y la trazabilidad obligatorias no se pueden construir retroactivamente; requieren planificación previa rigurosa y control formal de cambios.

---

## 3. Resumen de decisiones

| Caso | Metodología | Factor decisivo |
|---|---|---|
| Sistema de inventarios estable | Cascada | Requisitos estables y conocidos |
| Comercio electrónico en evolución | Scrum | Requisitos volátiles y necesidad de valor temprano |
| Software médico regulado | Híbrida (Cascada + iteración interna) | Cumplimiento normativo y trazabilidad obligatoria |

**Conclusión:** la metodología no se elige por moda sino por el grado de incertidumbre del proyecto. A mayor volatilidad de los requisitos, mayor conveniencia de un enfoque adaptativo; a mayor exigencia de previsibilidad, trazabilidad o cumplimiento normativo, mayor conveniencia de un enfoque predictivo.
