
---

# El precio antes del descuento: un cálculo inverso

🎯 **Descripción**  
Este proyecto es un ejercicio práctico para recordar las bases de **JavaScript Vanilla** mientras se explora la funcionalidad de **Astro.js** para crear páginas ligeras y dinámicas. El objetivo principal es calcular el precio original de un producto después de aplicar un descuento, mostrando el resultado de forma clara y funcional.

💡 **Contexto**  
A menudo, trabajando con frameworks modernos como **Next.js** o **Angular**, olvidamos lo importante que es mantener fresca nuestra lógica en **JavaScript Vanilla**. Este proyecto es un recordatorio de cómo resolver problemas simples de una manera directa y sin depender de frameworks.

---

## 🚀 **Características**
- Calcula el precio original de un producto después de un descuento.
- Implementación con **JavaScript Vanilla** para practicar lógica fundamental.
- Usa **Astro.js** para combinar contenido estático y dinámico.
- Resultado renderizado en una interfaz limpia y sencilla.

---

## 🛠️ **Tecnologías utilizadas**
- [JavaScript Vanilla](https://developer.mozilla.org/es/docs/Web/JavaScript)  
- [Astro.js](https://astro.build)  

---

## 📋 **Instrucciones de uso**
1. **Clona este repositorio**:
   ```bash
   git clone https://github.com/hnkatze/reverse_percent.git
   ```
2. **Navega al directorio del proyecto**:
   ```bash
   cd reverse_percent
   ```
3. **Instala las dependencias**:
   ```bash
   npm install
   ```
4. **Ejecuta el proyecto**:
   ```bash
   npm run dev
   ```
5. **Abre tu navegador** en [http://localhost:3000](http://localhost:3000) para ver la aplicación.

---

## 📐 **Lógica del cálculo**
El cálculo del precio original utiliza la fórmula:
```math
\text{Precio Original} = \frac{\text{Precio Final}}{1 - \text{Tasa de Descuento}}

```
Por ejemplo:  
Si un producto cuesta **$85** con un descuento del **15%**, el precio original es:

```math
\frac{85}{1 - 0.15} = \frac{85}{0.85} = 100
```
---

## 🖼️ **Estructura del proyecto**
```
├── public/
├── src/
│   ├── components/
│   ├── layouts/
│   ├── pages/
│       └── index.astro
├── package.json
└── README.md
```

---

## 🤝 **Contribuciones**
¡Este proyecto es solo una práctica, pero si tienes ideas para mejorarlo, son más que bienvenidas!  
Abre un issue o envía un pull request para discutir cambios.

---

## 🌟 **Contacto**
Si quieres saber más sobre este proyecto o intercambiar ideas:  
Camilo H. - henriquezhector1@hotmail.com - linkedin.com/in/hnkatze/

---

