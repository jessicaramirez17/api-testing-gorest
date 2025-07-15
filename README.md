# 🧪 API Testing – GoRest

Este proyecto forma parte de mi portafolio como QA Junior. Consiste en la validación manual de los endpoints de la API pública [GoRest](https://gorest.co.in/) utilizando Postman.

---

## 🎯 Objetivo

Diseñar y ejecutar pruebas manuales sobre los endpoints de la API GoRest, simulando casos reales como la obtención, creación y validación de usuarios. Se trabajó con solicitudes públicas y autenticadas.

---

## 🛠 Herramientas utilizadas

- [Postman](https://www.postman.com/)
- Documentación oficial de GoRest API
- Notion (para registrar evidencia)
- GitHub (gestión de versiones y portafolio)

---

## 🧪 Casos de prueba realizados

| ID      | Método | Endpoint                   | Descripción                           | Resultado esperado   |
|---------|--------|----------------------------|---------------------------------------|-----------------------|
| API-001 | GET    | `/users`                   | Obtener lista de usuarios             | 200 OK                |
| API-002 | GET    | `/users/999999`            | Consultar usuario inexistente         | 404 Not Found         |
| API-003 | POST   | `/users`                   | Crear usuario válido (con token)      | 201 Created           |
| API-004 | POST   | `/users` (sin token)       | Crear usuario sin autenticación       | 401 Unauthorized      |
| API-005 | POST   | `/users` (datos inválidos) | Crear usuario con email inválido      | 422 Unprocessable     |

---

## 📁 Archivos incluidos

- `gorest_api_jessica_ramirez.postman_collection.json` → colección de Postman con los casos descritos.

---

## 📸 Evidencia

Las capturas de pantalla de cada ejecución se encuentran documentadas en [mi portafolio Notion](https://notion.so) (puedes personalizar este enlace si usas Notion públicamente).

---

## 👩‍💻 Autor

Jessica Andrea Ramírez Camacho  
[GitHub](https://github.com/jessicaramirez17)  
[LinkedIn](https://www.linkedin.com/in/jessica-ramírez-851898197)  
Correo: jesikandre17@gmail.com

---

## 🚀 Próximos pasos

- Agregar pruebas `PUT` y `DELETE`
- Documentar errores simulados en Trello o Jira
- Subir ejemplos automatizados con Postman test scripts o Cypress
