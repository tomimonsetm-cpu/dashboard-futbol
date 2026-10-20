⚽ Dashboard Interactivo de Fútbol – FIFA 15 → EA FC 26
Proyecto en desarrollo donde mezclo dos pasiones: el fútbol y los datos. Un dashboard interactivo construido con Python, Pandas y Plotly a partir de datasets públicos de valoraciones de FIFA / EA FC.

🔗 Demo en vivo: https://tomimonsetm-cpu.github.io/dashboard-futbol/

Qué se puede hacer
📈 Ver la evolución del nivel de las ligas (las 5 grandes + la Liga Profesional argentina)
🔎 Explorar rankings de jugadores por edición, liga, club y línea táctica
🧩 Armar el equipo ideal 4-3-3 en cancha
🏟️ Recorrer la historia de un club, edición por edición
⚔️ Comparar jugadores con un gráfico radar
📓 Notebook (código completo)


Todo el proceso está en `FIFA_STATS_HISTORICAS_corregido.ipynb`, con cada línea comentada:

Carga y unificación de FIFA 15 a EA FC 26

Limpieza: posiciones, arqueros, nombres de ligas, IDs y nacionalidad

Diagnóstico de calidad de datos

Generación del dashboard HTML
![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)
> Los datasets originales no están en el repositorio (peso y licencias). Para ejecutar el notebook hay que subir los archivos `.zip` de origen a Colab; las instrucciones están en la primera celda.
Archivos
`index.html`: el dashboard publicado con GitHub Pages
`FIFA_STATS_HISTORICAS_corregido.ipynb`: el notebook de Python
Stack
Python · Pandas · Plotly · HTML/CSS/JavaScript (sin backend)
Autor
Tomás Monserrat · LinkedIn
