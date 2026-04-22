## Impacto

Una deficiente organización en la distribución de tareas dentro del equipo de desarrollo genera un impacto directo en el avance del proyecto. La falta de una planificación adecuada puede provocar desbalance en la carga de trabajo, duplicación de esfuerzos o retrasos en la implementación de módulos clave.

Esto repercute principalmente en el incumplimiento de los tiempos establecidos, ya que una mala estimación del esfuerzo requerido para cada módulo dificulta la correcta integración del sistema en las etapas finales. Un retraso en el sistema también implica que la empresa no pueda utilizar el sistema en el tiempo estipulado y retrase en ciertos aspectos la productividad de la empresa y la organización de tiempos del área administrativa.

Asimismo, no considerar desde el inicio fases importantes como pruebas, validación y presentación de módulos incrementa el riesgo de errores en etapas avanzadas del desarrollo. La ausencia de documentación clara sobre el funcionamiento de cada componente del sistema complica la identificación y solución de fallas, afectando la calidad del producto final.

En consecuencia, estos factores no solo impactan en el tiempo de entrega, sino también en la eficiencia del equipo y en la mantenibilidad del sistema desarrollado.

## 4. Causa Raíz

Para identificar el origen del incidente en la gestión de proyectos de grama sintética, se aplicó la técnica de los **"5 Porqués"**, permitiendo desglosar el problema desde el síntoma superficial hasta la falla estructural del negocio.

### Análisis de los 5 Porqués

1. **¿Por qué hubo un retraso crítico en la entrega de la obra y errores en la facturación al cliente?**
   Porque los datos de inventario de rollos de grama y la disponibilidad del equipo de instalación no estaban sincronizados al momento de generar la orden.

2. **¿Por qué la información de inventario y personal no estaba sincronizada?**
   Porque cada área maneja su propia información en archivos locales e independientes, lo que genera duplicidad y datos contradictorios.

3. **¿Por qué se utilizan archivos locales independientes para áreas tan críticas?**
   Porque el flujo de trabajo actual depende de procesos manuales y herramientas no integradas que no permiten el flujo de datos en tiempo real entre el catálogo de precios y la asignación de personal.

4. **¿Por qué no existe una comunicación automatizada entre el catálogo, los precios y el personal?**
   Porque el negocio ha crecido a una escala medio-grande, pero los procesos administrativos siguen operando bajo una estructura artesanal diseñada para proyectos pequeños.

5. **¿Por qué los procesos siguen siendo artesanales a pesar del crecimiento del negocio? (Causa Raíz)**
   Debido a la **ausencia de un sistema de gestión profesional (ERP/Software Centralizado)** diseñado para integrar de forma modular el manejo de personal, facturación, quejas de clientes, catálogo y precios. La falta de una infraestructura tecnológica unificada impide la escalabilidad y el control de calidad en proyectos de gran envergadura.

---

**Conclusión del Análisis:**
El incidente no fue un error humano aislado, sino una consecuencia inevitable de la desconexión sistémica. La falta de una plataforma centralizada de gestión profesional impide que las áreas críticas del negocio (como la colocación de grama y el manejo de precios) se comuniquen, resultando en ineficiencias operativas y pérdida de control sobre la rentabilidad del proyecto.
 
## Acciones tomadas para solucionarlo
Durante el incidente, el equipo tomó medidas inmediatas para reducir el impacto generado por la falta de sincronización entre las áreas del negocio. Como primer acción, se decidió suspender temporalmente la generación automática de órdenes y facturación, con el objetivo de evitar la propagación de errores en los datos.
Posteriormente, se optó por implementar un control manual provisional, en el cual se verificaba la disponibildad de invetario de rollos grama y la asignación del personal antes de confirmar pedido o proyecto. De manera simultanea, el equipo técnico realizó una revisión de los archivos loclaes utilizados por cada área, con el fin de identificar inconsistencias en la información y unificar los datos más relevantes en un solo registro temporal.
Asimismo, se estableció una comunicación directa entre las áreas involucradas (inventario, facturación y asignación de personal), permitiendo coordinar las actividades de forma más controlada mientras se solucionaba el problema. Finalmente, una vez corregidas las inconsistencias más críticas, se validó la información actualizada y se reanudó el flujo de trabajo, asegurando que las operaciones continuaran de manera más ordenada hasta la implementación de una solución definitiva.
