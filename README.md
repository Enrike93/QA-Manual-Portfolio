#  Portafolio de Pruebas QA Manual 

##  Descripción del Proyecto
Este repositorio contiene el diseño, la suite de pruebas manuales, la matriz de ejecución, los reportes de defectos y las evidencias visuales desarrollados para la plataforma e-commerce [SauceDemo](https://www.saucedemo.com/).

El objetivo del proyecto es validar la funcionalidad clave del flujo de compras, gestión de sesiones, seguridad básica (XSS y control de acceso por URL) y reglas de negocio.

---

## 📊 Resumen de Ejecución (Métricas)

| Métrica | Valor |
| :--- | :--- |
| **Total de Casos de Prueba Ejecutados** | 9 |
| **Casos Exitosos (Pass)** | 7 |
| **Casos Fallidos (Fail)** | 2 |
| **Porcentaje de Aprobación (% Pass Rate)** | **77.7%** |

---

##  Estructura del Repositorio

* **`Casos de P.xlsx`**: Matriz principal en Excel con el detalle completo de los 9 casos de prueba (precondiciones, datos de prueba, pasos, resultados esperados/obtenidos y prioridades).
 * **`/Bug-reports/`**: Documentación técnica detallada de los errores detectados durante las pruebas:
  * [Reporte Completo de Defectos](./Bug-reports/)
* **`bug_tienda_rota_problem_user.png`**: Captura de pantalla de la falla de interfaz y consola del BUG-001.
* **`checkout_vacio_fail.png`**: Captura de pantalla del comportamiento anómalo en el checkout del BUG-002.

---

## 🛠️ Herramientas y Metodologías Aplicadas
* **Gestión & Documentación:** Markdown, Microsoft Excel / Google Sheets
* **Análisis Técnico:** Chrome DevTools (consola JS y red)
* **Estrategias de Pruebas:** Pruebas Funcionales, Happy Path, Pruebas de Frontera/Seguridad (XSS/Auth), Reglas de Negocio y Pruebas Negativas.

---
##  Pruebas de API con Postman

Se diseñó y ejecutó una suite de pruebas de API utilizando **ReqRes**:
- **Petición GET:** Validación de código de respuesta `200 OK` y estructura de datos JSON de usuarios.
- **Petición POST:** Envío de payload en formato JSON para la creación de registros (`201 Created`).
* **Colección de Postman:** [Ver archivo JSON de la colección](./Postman_Collection.json)

##  Contacto / Enlaces
- **Perfil de LinkedIn:**([linkedin.com/in/enrique-obregon-04358a322/](https://www.linkedin.com/in/enrique-obregon-04358a322/))
* Ubicación : Novi Sad, Serbia.
* Email: obregonenrique251@gmail.com
* Telefono :+381 606746509
