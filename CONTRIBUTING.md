# Guía de Contribución

¡Gracias por tu interés en contribuir a Masco Styles! Esta guía te ayudará a entender el proceso de contribución.

## Cómo Contribuir

1. **Fork del repositorio**
   - Crea un fork del proyecto a tu cuenta de GitHub

2. **Clona tu fork**
   ```bash
   git clone https://github.com/TU-USUARIO/masco-styles.git
   cd masco-styles
   ```

3. **Instala las dependencias**
   ```bash
   npm install
   ```

4. **Crea una rama para tu contribución**
   ```bash
   git checkout -b feature/nombre-funcionalidad
   ```

5. **Realiza tus cambios**
   - Asegúrate de seguir las convenciones de código del proyecto
   - Ejecuta el desarrollo local con `npm start`

6. **Haz commit de tus cambios**
   ```bash
   git commit -m "Descripción clara de los cambios"
   ```

7. **Sube tus cambios a tu fork**
   ```bash
   git push origin feature/nombre-funcionalidad
   ```

8. **Crea un Pull Request**
   - Visita tu fork en GitHub y crea un Pull Request a la rama principal del repositorio original

## Convenciones de Código

- Utilizamos Tailwind CSS para estilos
- Sigue la estructura de carpetas existente
- Mantén la consistencia con el estilo de diseño
- Mantén los componentes modulares y reutilizables

## Informes de Errores

Si encuentras un error, crea un issue proporcionando:
- Descripción clara y concisa del error
- Pasos para reproducir el problema
- Comportamiento esperado vs. comportamiento actual
- Capturas de pantalla si aplica
- Información del entorno (navegador, sistema operativo, etc.)

## Solicitud de Funcionalidades

Las nuevas funcionalidades son bienvenidas. Crea un issue describiendo la funcionalidad deseada antes de comenzar a trabajar en ella.

## Preguntas

Si tienes alguna pregunta, no dudes en crear un issue con la etiqueta "pregunta".

¡Gracias por contribuir!
