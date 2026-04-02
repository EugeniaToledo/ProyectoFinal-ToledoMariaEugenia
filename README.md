# ProyectoFinal-ToledoMariaEugenia : Facebook Lite - Conectividad Global
QA Project: Testing funcional de Facebook Lite y pruebas de API con Postman. Metodología Ágil (Jira) y versionado en Git
* **Nombre:** María Eugenia Toledo
* **Comisión:** 202510
* **Profesor:** Leandro Fabián Layerle
---
## 🎯 Objetivo del Testing
Validar la robustez, usabilidad y eficiencia de las funciones de interacción social en la aplicación **Facebook Lite**. El enfoque principal fue asegurar que los usuarios puedan descubrir personas, gestionar amistades y comunicarse de manera efectiva en dispositivos de recursos limitados, cumpliendo con la épica de **Conectividad Global**.

## 🔍 Alcance y Entorno de Prueba
* **Alcance Funcional:** Módulos de Búsqueda Global, Gestión de Amistades, Mensajería Directa e Interacción en Grupos.
* **Entorno de Prueba:** Tablet Android (Pruebas de Interfaz) y Postman (Testing de API sobre Fake Store API).
* **Gestión Ágil:** Uso de **Jira** para la creación de Historias de Usuario, Criterios de Aceptación y reporte de defectos.

---

## 📊 Resumen de Ejecución
De acuerdo a la matriz de pruebas ejecutada en la tablet Android:

| Estado | Cantidad |
| :--- | :--- |
| ✅ **Exitosos (OK)** | 30 |
| ❌ **Fallidos (FAIL)** | 8 |
| 🚫 **Bloqueados** | 2 |
| **TOTAL** | **40** |
## 🏁 Conclusión General
**¿El producto está listo para producción?**
**No totalmente.** Si bien la mayoría de las funciones críticas (Mensajería y Amistad) operan correctamente, se detectaron **varios defectos** de severidad media en el motor de búsqueda. Se recomienda la corrección de estos errores de sincronización antes del despliegue final para garantizar la propuesta de valor de la app.

---

## 🛠️ Tecnologías y Herramientas Utilizadas
* **Gestión:** Jira (Metodología Ágil)
* **Documentación:** Microsoft Excel (Matriz de pruebas y Bugs)
* **API Testing:** Postman & Fake Store API
* **Versionado:** Git & GitHub (Flujo de ramas y Pull Requests)