Plan de Cursada - Téc./Lic. en Informática (UNAHUR)

Este proyecto es una herramienta visual interactiva para el seguimiento de la trayectoria académica en la carrera de Informática de la Universidad Nacional de Hurlingham (UNAHUR). Permite visualizar correlatividades, gestionar cuatrimestres y monitorear el progreso hacia el título intermedio y final.

🚀 Funcionalidades Principales
Grafo de Correlatividades Interactivo: Visualización dinámica del plan de estudios con nodos que muestran el estado actual de cada materia.

Gestión de Cursada: Organiza tus materias por cuatrimestres, permitiendo marcar estados como:

Promocionada / Final Aprobado

Cursada (Final pendiente)

Recursada / A recursar

Indicadores de Progreso:

Cálculo automático de avance para el Título Intermedio (Tecnicatura).

Cálculo de progreso total para la Licenciatura.

Cálculo automático del promedio académico basado en las notas cargadas.

Personalización y Edición: ¿El plan cambió? Puedes editar manualmente las correlatividades de cualquier materia directamente desde el grafo.

Persistencia de Datos: Exporta e importa tus datos en formato JSON para no perder tu avance o migrarlo entre dispositivos.

🛠️ Instructivo de Uso
Exploración: Haz clic en cualquier materia dentro del grafo para abrir el panel de detalles.

Carga de Materias:

Utiliza la sección de "Cuatrimestres" en la barra lateral para agregar un nuevo periodo (ej. "1C 2026").

Dentro de cada cuatrimestre, selecciona la materia correspondiente y su estado.

Seguimiento: El grafo se actualizará automáticamente:

Las materias habilitadas se iluminarán en cian.

Las materias bloqueadas aparecerán en gris oscuro.

Copia de Seguridad: Recuerda usar el botón "Exportar datos" periódicamente para guardar un archivo plan_cursada_backup.json con tu configuración actual.

📋 Información Técnica
Tecnologías: HTML5, CSS3 (Grid/Flexbox) y JavaScript nativo (Vanilla JS).

Diseño: Interfaz optimizada para escritorio con diseño responsivo.

Estructura: Los datos del plan de estudios están definidos en una constante SUBJECTS dentro del código, facilitando su mantenimiento si el plan de la universidad llega a modificarse.

⚖️ Licencia
Este proyecto está bajo la licencia Creative Commons Attribution 4.0 International (CC BY 4.0). Eres libre de compartir y adaptar este material, siempre que se atribuya adecuadamente al autor original.

Desarrollado para estudiantes de UNAHUR.

Instrucciones para subirlo a tu GitHub:
Crea un nuevo repositorio en tu perfil de GitHub.

Crea un archivo llamado index.html y pega tu código ahí.

Crea el archivo README.md (puedes copiar el texto de arriba).

Si deseas que la herramienta sea accesible online, ve a la Configuración de tu repositorio -> Pages y selecciona la rama main para activarlas. ¡Tu plan de cursada estará disponible en una URL pública en segundos!
