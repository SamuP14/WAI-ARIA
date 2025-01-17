# Mejora de Accesibilidad en Elementos de Bootstrap con WAI-ARIA

Este proyecto muestra cómo mejorar la accesibilidad de elementos comunes de Bootstrap mediante la implementación de atributos WAI-ARIA.

## Elementos Mejorados
1. **Botón**
   - Se añadió `aria-label` para describir su función.
   - `role="button"` se hizo explícito.
   - `tabindex="0"` asegura la navegabilidad con teclado.

2. **Menú Desplegable**
   - `aria-haspopup`, `aria-expanded` y `aria-controls` fueron añadidos al botón para manejar el estado del menú.
   - Se definió `role="menu"` y `role="menuitem"` para identificar el propósito del contenedor y sus elementos.

3. **Alerta**
   - `aria-live="assertive"` asegura que los lectores de pantalla anuncien las alertas de forma inmediata.
   - `aria-atomic="true"` permite que las alertas se lean completas.

4. **Pestañas**
   - Atributos como `role="tablist"`, `role="tab"` y `role="tabpanel"` identifican el propósito de las pestañas y sus paneles.
   - `aria-controls` y `aria-labelledby` establecen relaciones entre pestañas y contenido.

5. **Barra de Navegación**
   - `role="navigation"` define su propósito como contenedor de navegación.
   - `aria-label` describe la función de la barra.
   - `aria-expanded` y `aria-controls` controlan el estado del botón de colapso.

