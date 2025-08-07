# Accessible Form UI

Un formulario moderno y accesible, construido con HTML y CSS puro, diseñado para mejorar la experiencia del usuario al actualizar su perfil. Incluye una barra de progreso circular y una checklist de tareas completadas para fomentar la interacción y seguimiento del usuario.

[![Project](https://roadmap.sh/projects/accessible-form-ui)](https://roadmap.sh/projects/accessible-form-ui)

---

## 🎯 Características

- Formulario accesible y responsivo
- Campos para nombre, correo y contraseña
- Barra de progreso circular con porcentaje de completitud
- Checklist de tareas completadas
- Diseño moderno con estilos personalizables
- Construido sin JavaScript
- Totalmente compatible con todos los navegadores modernos

---

## 🚀 Cómo usar

1. Cloná este repositorio o descargá los archivos `.zip`
2. Abrí `index.html` en tu navegador local
3. Personalizá el contenido del formulario según tus necesidades
4. Modificá estilos desde `style.css` para cambiar colores, fuentes o tamaños
5. Agregá más campos o tareas a la checklist si es necesario

---

## 🔧 Personalización

- **Colores**: Los colores principales (#9900ff y derivados) pueden modificarse desde el CSS para adaptarse a tu marca.
- **Checklist**: Actualizá los ítems dentro del `<ul>` para reflejar pasos personalizados del usuario.
- **Progreso**: La barra es estática visualmente (72%) pero puede dinamizarse fácilmente con JS en futuras versiones.
- **Fuentes**: Utiliza la fuente [Ubuntu](https://fonts.google.com/specimen/Ubuntu) importada desde Google Fonts.

---

## 📁 Estructura del Proyecto

```
accessible-form-ui/
├── index.html               # Archivo HTML principal
├── style.css                # Estilos CSS del formulario y progreso
├── assets/
│   └── preview.png          # Imagen opcional del diseño final (añadí la tuya)
└── README.md                # Este archivo
```

---

## 🧪 Ejemplo de implementación

```html
<form action="#" method="post">
  <label for="name">Full Name:</label>
  <input
    type="text"
    id="name"
    name="name"
    placeholder="What should we call you?"
    required
  />

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" placeholder="david@rogaci.com" />

  <label for="password">Enter Password:</label>
  <input
    type="password"
    id="password"
    name="password"
    placeholder="Enter a secure password"
    required
  />

  <label for="confirmPassword">Confirm Password:</label>
  <input
    type="password"
    id="confirmPassword"
    name="confirmPassword"
    placeholder="Repeat secure password"
    required
  />
</form>
```

---

## 📸 Captura de pantalla

> Podés agregar una imagen en `assets/preview.png` para que los visitantes del repositorio vean cómo luce el formulario.

---

## 📜 Licencia

Este proyecto está bajo la [Licencia Apache](LICENSE). Podés usarlo, modificarlo y distribuirlo libremente.

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Podés abrir un `issue` o enviar un `pull request` para mejorar el diseño, agregar funcionalidades con JS, o hacerlo aún más accesible.

---

Hecho con ❤️ por [David Rogaci](https://github.com/davidrogaci)
