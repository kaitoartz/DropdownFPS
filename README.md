# FPS Selector for Unity

👋 ¡Hola, desarrolladores de Unity! Soy [Tu Nombre], y estoy emocionado de compartir este proyecto contigo.

🚀 **¿Quieres estar al día con mis próximos proyectos de Unity?** ¡Sígueme en mis redes sociales!

- 🐦 Twitter: [@K41T0M](https://x.com/K41t0M)
- 📷 Instagram: [@kaitoartzz](https://www.instagram.com/kaitoartzz/#)
- 🎥 YouTube: [KaitoArtz](https://www.youtube.com/channel/UCUTRLuPwGw9LKCt8ictOaZA)
- 🔗 LinkedIn: [Tu Perfil de LinkedIn](https://www.linkedin.com/in/TuPerfilDeLinkedIn)

No te pierdas mis futuros proyectos y tutoriales que te ayudarán a mejorar tus habilidades en Unity. ¡Vamos a crear juegos increíbles juntos! 🎮✨

---

Este repositorio contiene un script de C# diseñado para Unity (versión 2021.3.15f1 o superior) que permite a los desarrolladores seleccionar y ajustar el framerate (FPS) de su juego de manera sencilla. Con este script, puedes ofrecer a los jugadores la opción de cambiar entre diferentes configuraciones de FPS a través de un menú desplegable en la UI.

## Características
- **Selección de FPS**: Los jugadores pueden elegir entre 30, 60, 120 FPS o desbloquear el FPS.
- **Integración Sencilla**: Fácil de integrar en cualquier proyecto de Unity.
- **Persistencia de Configuración**: La selección de FPS se guarda y se aplica automáticamente en futuras sesiones del juego.

## Instalación

1. **Descargar el Script**: Clona este repositorio o descarga el archivo `FPSSelector.cs`.
2. **Importar a Unity**: Coloca el archivo `FPSSelector.cs` en la carpeta `Scripts` de tu proyecto de Unity.
3. **Agregar el Script a un GameObject**:
   - Crea un nuevo `GameObject` vacío en tu escena o utiliza uno existente.
   - Arrastra el script `FPSSelector` al `GameObject`.
4. **Configurar el Dropdown en la UI**:
   - En tu escena, añade un componente `TMP_Dropdown` a la UI.
   - En el inspector, asigna el `TMP_Dropdown` al campo `fpsDropdown` en el script `FPSSelector`.

## Uso

1. **Configuración Inicial**:
   - Al iniciar el juego, el script cargará la última configuración de FPS seleccionada.
   - El dropdown se ajustará automáticamente al valor correspondiente.

2. **Cambio de FPS**:
   - Los jugadores pueden seleccionar un valor diferente en el dropdown.
   - Para aplicar la nueva configuración de FPS, llama al método `ApplyFPSSetting()` desde el script.

## Personalización

Puedes modificar el script para añadir o eliminar opciones de FPS según las necesidades de tu proyecto. Simplemente ajusta los métodos `GetFPSFromDropdownIndex` y `GetDropdownIndexFromFPS` en el script.

## Requisitos

- Unity 2021.3.15f1 o superior.
- `TextMeshPro` debe estar instalado en tu proyecto para usar `TMP_Dropdown`.

## Contribuciones

¡Las contribuciones son bienvenidas! Si tienes mejoras, ideas, o encuentras un bug, siéntete libre de abrir un issue o enviar un pull request.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [Licencia](LICENSE.md) para más detalles.

## Políticas de Privacidad

Este proyecto no recopila información personal ni técnica de los usuarios. Para más detalles, consulta nuestras [Políticas de Privacidad](SECURITY.md).
