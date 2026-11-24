# 01 · Planteamiento del problema

## 1. Contexto

El vivero que dio origen a este proyecto opera con base en **donaciones de árboles y plantas**. Cada entrega se registra en una solicitud física (en papel) que luego se digita a mano en un archivo de Excel.

Esta situación es común en viveros comunitarios, ambientales y municipales, por eso **Germina** se plantea como un sistema que puedan usar **varios viveros**, cada uno con su propia información.

## 2. Problema central

La gestión manual y desorganizada del vivero impide conocer en tiempo real **qué plantas hay, cuáles se donan más y a quién se le han donado**, lo que dificulta la toma de decisiones y la elaboración de los informes mensuales.

## 3. Causas

- Las solicitudes de donación se diligencian en papel y se digitan después, lo que consume tiempo y genera retrasos.
- Las hojas físicas se extravían y se pierde la evidencia de la entrega.
- El Excel queda desactualizado por falta de tiempo y de un proceso ordenado.
- No existe un registro unificado de beneficiarios, que en muchos casos se repiten.
- No hay alertas de inventario bajo ni control de existencias por especie.
- No hay forma de identificar fácilmente qué especies son las más solicitadas.
- La planeación de nuevas especies a cultivar se hace sin datos.

## 4. Efectos

- Inventario desconocido o desactualizado de árboles y plantas.
- Informes mensuales lentos, incompletos o poco confiables.
- Pérdida de la evidencia de entrega (firmas en papel).
- Falta de seguimiento a las personas que reciben donaciones: no se sabe si las plantas sobrevivieron ni se mantiene el vínculo.
- Decisiones de siembra y reposición basadas en la intuición y no en datos.

## 5. Pregunta problema

¿Cómo puede un vivero digitalizar y centralizar el registro de donaciones, el inventario y el seguimiento a sus beneficiarios para reducir el tiempo administrativo, evitar pérdidas de información y generar informes y decisiones basadas en datos?

## 6. Solución propuesta

Un **software web de gestión de viveros**, usable desde celular y computador, que centraliza en un solo sistema las donaciones, el inventario, los beneficiarios y los informes.

| Problema | Funcionalidad de la solución |
|---|---|
| Solicitudes en papel que se pierden y toca digitar | Formulario digital de entrega/donación que se llena directamente desde celular o computador, sin doble digitación |
| Firma en papel como evidencia | Foto o adjunto de evidencia (la persona con la planta entregada) que reemplaza la firma y queda guardado en el registro |
| Personas que se repiten, sin historial | Directorio de beneficiarios (CRM): ficha única por persona con su historial de donaciones, evitando duplicados |
| Sin seguimiento posterior | Recordatorios internos y envío de WhatsApp (por ejemplo, cada 6 meses) para dar seguimiento a quienes recibieron plantas |
| Inventario desactualizado | Inventario en tiempo real por especie: cada donación descuenta existencias y cada ingreso las suma |
| Sin alertas | Notificaciones de stock bajo configurables por especie |
| Difícil registrar nuevas especies | Módulo de ingreso de plantas con foto, cantidad, fecha y datos de la especie |
| Informes mensuales difíciles | Generador de informes de donaciones (por mes, especie, beneficiario) exportables a PDF y Excel |
| No se sabe qué plantas son las favoritas | Panel con gráficas: donadas vs. disponibles, especies más solicitadas y sugerencia de cuáles empezar a cultivar |

### Flujo básico del sistema

1. Ingreso de plantas al inventario (especie, cantidad, foto).
2. Registro de donación: se busca o crea el beneficiario, se seleccionan especies y cantidades, y se adjunta la foto de entrega.
3. El inventario se actualiza automáticamente.
4. El sistema alerta cuando una especie está por agotarse.
5. A los 6 meses, el sistema recuerda hacer el seguimiento y facilita enviar el WhatsApp.
6. A fin de mes se genera el informe con un clic y se consultan las gráficas.

## 7. Objetivos

**Objetivo general:** desarrollar un software de administración de viveros que digitalice y centralice el registro de donaciones, el inventario y el seguimiento de beneficiarios, para mejorar el control y la presentación de informes.

**Objetivos específicos:**

1. Digitalizar el formulario de donación con evidencia fotográfica de entrega.
2. Implementar un directorio de beneficiarios que unifique y dé seguimiento a los beneficiarios recurrentes.
3. Controlar el inventario en tiempo real con alertas de existencias.
4. Automatizar la generación de informes mensuales de donaciones.
5. Visualizar en gráficas las especies más donadas y las existencias para orientar la producción.
6. Permitir que varios viveros usen el sistema de forma independiente y segura.

## 8. Beneficios esperados

- Reducción del tiempo dedicado a digitar y organizar información.
- Cero pérdida de evidencia de entregas.
- Informes mensuales generados en minutos.
- Inventario confiable y decisiones de cultivo basadas en datos.
- Relación más cercana y continua con los beneficiarios.