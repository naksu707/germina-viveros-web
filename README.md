<div align="center">

# 🌱 Germina
### Software de gestión para viveros: donaciones, inventario y seguimiento a beneficiarios

<p>
<img src="https://img.shields.io/badge/Estado-En%20planeación-8BC34A?style=for-the-badge" />
<img src="https://img.shields.io/badge/Idioma-Español-2E7D32?style=for-the-badge" />
<img src="https://img.shields.io/badge/Hecho%20para-Colombia-FCD116?style=for-the-badge" />
</p>

</div>

> [!NOTE]
> **Estado: en planeación 🚧** · Por ahora el repositorio contiene la definición del problema, la solución y los objetivos. Ver [`docs/01-planteamiento-del-problema.md`](docs/01-planteamiento-del-problema.md).

---

## 💡 El problema

Muchos viveros entregan árboles y plantas en donación y registran cada entrega en **solicitudes de papel** que después alguien digita en un Excel. En el camino:

- 📄 Las hojas se pierden y con ellas la **evidencia de la entrega**.
- ⏳ El Excel queda **desactualizado** y nadie sabe con certeza qué plantas hay.
- 👥 Las mismas personas aparecen varias veces, **sin historial**.
- 📉 Los **informes mensuales** tardan y son poco confiables.
- 🌳 No se sabe qué especies son las más pedidas, así que **qué sembrar** se decide por intuición.
- 🤝 Después de entregar una planta no hay **seguimiento**: no se sabe si sobrevivió ni se mantiene el vínculo con la persona.

> **Pregunta problema:** ¿Cómo puede un vivero digitalizar y centralizar el registro de donaciones, el inventario y el seguimiento a sus beneficiarios para reducir el tiempo administrativo, evitar pérdidas de información y tomar decisiones basadas en datos?

---

## 🌿 La solución

**Germina** es una aplicación web, pensada para usarse también desde el celular, que reúne en un solo lugar las donaciones, el inventario, los beneficiarios y los informes. Está pensada para que **varios viveros** puedan usarla, cada uno con su propia información.

| Problema | Cómo lo resuelve Germina |
|---|---|
| Solicitudes en papel que se pierden y toca digitar | **Formulario digital de donación** desde el celular o el computador, sin doble digitación |
| Firma en papel como evidencia | **Foto de entrega** (la persona con su planta) guardada en el registro |
| Personas repetidas y sin historial | **Directorio de beneficiarios (CRM)**: una ficha por persona con su historial de donaciones |
| Sin seguimiento después de la entrega | **Recordatorios de seguimiento** (por ejemplo, a los 6 meses) con mensaje de WhatsApp |
| Inventario desactualizado | **Inventario en tiempo real por especie**: cada donación descuenta y cada ingreso suma |
| Sin alertas | **Alertas de existencias bajas** configurables por especie |
| Difícil registrar especies nuevas | **Ingreso de plantas** con foto, cantidad, fecha y datos de la especie |
| Informes mensuales lentos | **Informes de donaciones** por mes, especie o beneficiario, exportables a PDF y Excel |
| No se sabe qué plantas son las favoritas | **Panel con gráficas**: donadas vs. disponibles, especies más pedidas y sugerencias de qué cultivar |

### Flujo básico

1. Ingreso de plantas al inventario (especie, cantidad, foto).
2. Registro de donación: se busca o crea el beneficiario, se eligen especies y cantidades, y se adjunta la foto de entrega.
3. El inventario se actualiza automáticamente.
4. El sistema alerta cuando una especie está por agotarse.
5. A los 6 meses, el sistema recuerda hacer el seguimiento y facilita enviar el WhatsApp.
6. A fin de mes se genera el informe con un clic y se consultan las gráficas.

---

## 🎯 Objetivos

**General:** desarrollar un software de administración de viveros que digitalice y centralice el registro de donaciones, el inventario y el seguimiento de beneficiarios, para mejorar el control y la presentación de informes.

**Específicos:**

1. Digitalizar el formulario de donación con evidencia fotográfica de entrega.
2. Implementar un directorio de beneficiarios que unifique y dé seguimiento a los beneficiarios recurrentes.
3. Controlar el inventario en tiempo real con alertas de existencias.
4. Automatizar la generación de informes mensuales de donaciones.
5. Visualizar en gráficas las especies más donadas y las existencias para orientar la producción.
6. Permitir que varios viveros usen el sistema de forma independiente.

---

## ✨ Beneficios esperados

- Menos tiempo digitando y organizando información.
- Cero pérdida de evidencia de entregas.
- Informes mensuales en minutos.
- Inventario confiable y decisiones de cultivo basadas en datos.
- Una relación más cercana y continua con los beneficiarios.

---

## 🗺️ Hoja de ruta

- [x] Planteamiento del problema, solución y objetivos
- [ ] Requisitos y modelo de datos
- [ ] Prototipo de pantallas
- [ ] Desarrollo
- [ ] Pruebas manuales y automatizadas
- [ ] Pruebas con un vivero real
- [ ] Despliegue

---

<div align="center">

Hecho por 💚 **[Maria Jose Ospina](https://github.com/naksu707)** 💚 y **[Valentina Herrera](https://github.com/Herre-3)**

</div>