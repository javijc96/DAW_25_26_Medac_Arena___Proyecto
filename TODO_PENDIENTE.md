# 📝 TODO List - GuardiApp Documentation

Lista de tareas pendientes para completar la documentación del TFG.

## 🖼️ 1. Fase Visual (Prioridad Alta)
*Estas tareas son necesarias para que el PDF no tenga huecos vacíos.*

- [ ] **Capturas de Interfaz (Frontend)**: Realizar capturas de pantalla de la aplicación real y guardarlas en `img/interfaz/`:
    - `login.png`
    - `dashboard_calendario.png`
    - `requests_inbox.png`
    - `admin_panel.png`
    - `gestion_usuarios.png`
    - `perfil.png`
- [ ] **Diagramas de Datos**: Exportar los diagramas desde MySQL/Workbench y guardarlos en sus carpetas:
    - `img/diagramas/EER/EER_v5.png` (Modelo Conceptual Entidad-Relación).
    - `img/diagramas/Datos/Diagrama-relacional.png` (Esquema Físico de Tablas).
- [ ] **Diagramas de Secuencia**: Generar los PNG a partir de los archivos `.wsd` en `img/diagramas/Secuencia/`.
- [ ] **Activar Imágenes en LaTeX**: Quitar el símbolo `%` de las líneas `\includegraphics` en los capítulos 6, 8 y 10.

## ✍️ 2. Contenido y Redacción (Prioridad Media)
- [ ] **Capítulo 20 (Anexos)**: Decidir y redactar el contenido. Sugerencias:
    - Manual de usuario básico.
    - Guía de instalación rápida (composer install, npm install, etc.).
    - Diccionario de términos técnicos.
- [ ] **Capítulo 5 (Requisitos)**: Revisar si algún requisito funcional ha cambiado tras la auditoría del código real (especialmente el flujo de intercambio mutuo).

## 🛠️ 3. Revisión Final (Prioridad Baja)
- [ ] **Bibliografía**: Comprobar que todos los archivos citados en el texto están en `references.bib`.
- [ ] **Compilación de Limpieza**: Ejecutar `pdflatex` tres veces seguidas para asegurar que el índice, la lista de tablas y las referencias cruzadas no tengan errores de "??".

---
*Buen trabajo esta semana. ¡Nos vemos el lunes!*
