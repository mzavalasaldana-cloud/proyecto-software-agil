# Manifiesto Ágil y su aplicación al proyecto

> Entregable 3 de la Guía de Laboratorio Nº 01.
> Referencia: <https://agilemanifesto.org/iso/es/manifiesto.html>

---

## 1. Los 4 valores del Manifiesto Ágil

1. **Individuos e interacciones** sobre procesos y herramientas.
2. **Software funcionando** sobre documentación exhaustiva.
3. **Colaboración con el cliente** sobre negociación contractual.
4. **Respuesta ante el cambio** sobre seguir un plan.

> Aunque valoramos los elementos de la derecha, valoramos más los de la izquierda. El Manifiesto establece prioridades, no exclusiones.

---

## 2. Los 12 principios (referencia)

1. Satisfacer al cliente mediante la entrega temprana y continua de software con valor.
2. Aceptar los cambios de requisitos, incluso en etapas tardías del desarrollo.
3. Entregar software funcionando con frecuencia, en plazos cortos.
4. Responsables de negocio y desarrolladores trabajan juntos a diario.
5. Construir proyectos en torno a personas motivadas, dándoles apoyo y confianza.
6. La conversación cara a cara es el método más eficiente de comunicación.
7. El software funcionando es la medida principal de progreso.
8. Los procesos ágiles promueven el desarrollo sostenible a ritmo constante.
9. La atención continua a la excelencia técnica mejora la agilidad.
10. La simplicidad —maximizar el trabajo no realizado— es esencial.
11. Las mejores arquitecturas y requisitos emergen de equipos autoorganizados.
12. El equipo reflexiona periódicamente sobre cómo ser más efectivo y ajusta su comportamiento.

---

## 3. Aplicación de 3 principios al proyecto de comercio electrónico

### Principio 3 — Entregar software funcionando con frecuencia

> *"Entregamos software funcional frecuentemente, entre dos semanas y dos meses, con preferencia al periodo de tiempo más corto posible."*

**Aplicación concreta en la plataforma:**

- El desarrollo se organiza en Sprints de 2 semanas y cada uno cierra con una versión desplegable en el entorno de pruebas.
- Plan de incrementos:
  - **Sprint 1:** registro de usuarios y catálogo de productos.
  - **Sprint 2:** carrito de compras y cálculo de totales.
  - **Sprint 3:** procesamiento y seguimiento de pedidos.
- Al final de cada Sprint el cliente prueba la versión real —no una maqueta— y su retroalimentación entra al Backlog del ciclo siguiente.
- **Efecto:** el negocio puede vender con el catálogo desde la semana 2, en lugar de esperar meses al sistema completo.

---

### Principio 2 — Aceptar los cambios de requisitos, incluso en etapas tardías

> *"Aceptamos que los requisitos cambien, incluso en etapas tardías del desarrollo. Los procesos ágiles aprovechan el cambio para proporcionar ventaja competitiva al cliente."*

**Aplicación concreta en la plataforma:**

- Situación: a mitad del desarrollo, el cliente necesita integrar una pasarela de pagos que no estaba prevista, porque la competencia ya la ofrece.
- Respuesta ágil: la nueva funcionalidad se escribe como historia de usuario, se estima y se prioriza en el Backlog; el Product Owner decide qué se posterga a cambio.
- No se reinicia la planificación completa ni se renegocia el contrato entero: se ajusta el orden de los Sprints siguientes.
- **Efecto:** el trabajo ya entregado conserva su valor y la plataforma incorpora el cambio del mercado en el ciclo siguiente, no al año siguiente.

---

### Principio 7 — El software funcionando es la medida principal de progreso

> *"El software funcionando es la medida principal de progreso."*

**Aplicación concreta en la plataforma:**

- Una historia solo se considera terminada si cumple la Definición de Terminado: código integrado, probado y desplegado en el entorno de pruebas.
- No cuentan como avance los documentos completados, los diagramas ni las tareas marcadas como hechas sin verificación.
- En la Revisión del Sprint se demuestra la aplicación en vivo —un pedido real recorriendo el flujo completo— en lugar de presentar diapositivas o informes de estado.
- **Efecto:** el avance reportado coincide con el avance real, y se evita el escenario clásico de "90 % terminado" durante meses.

---

## 4. Conclusión

Aplicar el Manifiesto en esta plataforma no significa eliminar la planificación ni la documentación, sino subordinarlas al objetivo de entregar valor utilizable. La entrega frecuente da retroalimentación temprana, la apertura al cambio convierte la volatilidad del mercado en ventaja competitiva, y medir el progreso por software funcionando mantiene la honestidad del avance. El resultado es un producto que evoluciona junto con las necesidades reales de los usuarios, reduciendo el riesgo de construir algo obsoleto o que no resuelve lo que el cliente necesita.
