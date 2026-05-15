# Práctica de Formulario de Contacto con JavaScript DOM

## 📋 Descripción

Este repositorio contiene una práctica de clase enfocada en el manejo del DOM con JavaScript. El objetivo es implementar la funcionalidad completa de un formulario de contacto, incluyendo validaciones, manejo de eventos y extracción de datos.

## 🎯 Objetivos de Aprendizaje

- Manipulación del DOM con JavaScript
- Selección de elementos del DOM
- Manejo de eventos (submit, input, change, etc.)
- Validación de formularios del lado del cliente
- Extracción y procesamiento de datos del formulario
- Aplicación de estilos dinámicos con JavaScript

## 🏗️ Estructura del Proyecto

```
proyecto-formulario/
│
├── index.html          # Estructura HTML del formulario (proporcionada)
├── css/
│   └── style.css      # Estilos CSS (proporcionados)
└── js/
    └── main.js        # Archivo JavaScript para implementar (A COMPLETAR)
```

## 📝 Funcionalidades a Implementar

### 1. Selección de Elementos del DOM
- Seleccionar el formulario
- Seleccionar todos los campos de entrada
- Seleccionar elementos para mostrar mensajes de error
- Seleccionar el mensaje de éxito

### 2. Validaciones Requeridas

El formulario incluye los siguientes campos que deben ser validados:

- **First Name**: Campo requerido, no puede estar vacío
- **Last Name**: Campo requerido, no puede estar vacío
- **Email Address**: Campo requerido, debe tener formato de email válido
- **Query Type**: Debe seleccionarse una opción (General Enquiry o Support Request)
- **Message**: Campo requerido, no puede estar vacío
- **Consent Checkbox**: Debe estar marcado para enviar el formulario

### 3. Manejo de Eventos

- Evento `submit` en el formulario
- Eventos de validación en tiempo real (opcional)
- Eventos para estilos interactivos en los radio buttons

### 4. Mostrar Mensajes de Error

- Mostrar mensajes de error específicos para cada campo inválido
- Ocultar mensajes de error cuando el campo sea válido
- Aplicar estilos de error (clases CSS ya proporcionadas)

### 5. Mensaje de Éxito

- Mostrar el mensaje de éxito cuando el formulario sea válido


## 💡 Conceptos Clave de JavaScript

- `document.getElementById()`
- `document.querySelector()` / `querySelectorAll()`
- `addEventListener()`
- `classList.add()` / `classList.remove()`
- `value` property
- `checked` property
- Expresiones regulares para validar email

## 🎨 Clases CSS Disponibles

- `.error-message`: Mostrar mensajes de error
- `.success-message`: Mostrar mensaje de éxito
- `.error`: Aplicar a inputs con error (borde rojo)

## ✅ Criterios de Evaluación

- [ ] Todos los campos se validan correctamente
- [ ] Los mensajes de error se muestran en los campos correspondientes
- [ ] El formulario no se envía si hay campos inválidos
- [ ] El mensaje de éxito se muestra cuando el formulario es válido
- [ ] El código está bien organizado y comentado
- [ ] Se utilizan funciones reutilizables


## 📚 Recursos Útiles

- [MDN - Document Object Model](https://developer.mozilla.org/es/docs/Web/API/Document_Object_Model)
- [MDN - Validación de formularios](https://developer.mozilla.org/es/docs/Learn/Forms/Form_validation)
- [MDN - EventTarget.addEventListener()](https://developer.mozilla.org/es/docs/Web/API/EventTarget/addEventListener)

## 👨‍💻 Autor

Práctica de clase - Desarrollo Web
Coach Kenia Paiz
---

**Nota**: Esta práctica está diseñada para ser completada en clase con la guía del instructor. El HTML y CSS ya están proporcionados, el enfoque está en implementar toda la lógica con JavaScript.