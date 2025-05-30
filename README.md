# Accessible form ui

En este proyecto, deberás crear un formulario de interfaz de usuario utilizando sólo HTML y CSS. El formulario incluirá campos para un nombre completo, correo electrónico, contraseña y confirmación de contraseña, junto con un botón para cambiar la visibilidad del texto de la contraseña. Además, el formulario incluirá una barra de progreso de integridad y una lista de comprobación de los requisitos que deben cumplirse para que el formulario esté completo al 100%. Aunque esta versión del formulario no será funcional, será un componente de interfaz de usuario estático que podrá mejorarse con JavaScript en el futuro.

El objetivo de este proyecto no es sólo ayudarte a practicar tu HTML y CSS, sino también centrarte en la creación de un formulario accesible que sea fácil de usar para todos los usuarios, incluidos aquellos con discapacidades. A continuación se muestra una maqueta de la interfaz de usuario del formulario que debe crear:

![form-components-7t4b3](https://github.com/user-attachments/assets/14c0c552-e440-4124-a87b-b571c0037580)


Accessibility Guidelines

You should read up on accessibility guidelines and best practices before starting this project. However, here are some key points to keep in mind while creating an accessible form UI:

- Labeling: Ensure that each form field has a corresponding <label> element that is clearly associated with the field using the for attribute.
- Focus State: Style the focus state of each input field so that users navigating with a keyboard can easily see which field is currently active.
- Error Messaging: Consider adding space for error messages that can be displayed when a user inputs invalid data. These messages should be clearly associated with the relevant input field.
- ARIA Attributes: Use ARIA (Accessible Rich Internet Applications) attributes where necessary, such as aria-required for required fields and aria-invalid for fields with errors.
- Color Contrast: Ensure that the color contrast between text and background is sufficient to meet WCAG (Web Content Accessibility Guidelines) standards, making the form readable for users with visual impairments.
- Interactive Elements: Make sure that the button to show/hide the password is accessible via keyboard and screen readers, providing clear feedback on the current state (e.g., “Password is hidden” or “Password is visible”).

Una vez hecho esto, puedes probar la interfaz de usuario del formulario utilizando un lector de pantalla o extensiones del navegador como Axe o Lighthouse para comprobar si hay problemas de accesibilidad y hacer los ajustes necesarios.

> [!NOTE]
> Este proyecto es obtenido de la página de <a href="https://roadmap.sh/projects/accessible-form-ui">roadmap.sh</a>

## Soluciones hechas por la comunidad
|Usuario|Repositorio| Website | Figma|
|-------|-----------|---------|------|
