# Gestiona-Informacion-Mediante-el-uso-de-Software-en-Linea
Repositorio para practicas y ejercicios de la materia gestiona informacion

GIT HUB

Caracteristicas, Ventajas y desventajas de Git hub

GitHub se ha consolidado como el epicentro del desarrollo colaborativo moderno al ofrecer un ecosistema integral que va más allá del simple alojamiento de código. Su arquitectura permite que cualquier desarrollador, sin importar su ubicación geográfica, pueda contribuir a proyectos de gran escala mediante un flujo de trabajo estructurado que garantiza la integridad del software a través de revisiones por pares y pruebas automatizadas. Esta visibilidad no solo fomenta la innovación y el aprendizaje colectivo dentro del movimiento de código abierto, sino que también otorga a las empresas un control granular sobre sus activos digitales y la capacidad de acelerar sus ciclos de lanzamiento mediante la integración continua. No obstante, esta potencia conlleva la responsabilidad de dominar la lógica de ramas y fusiones de Git, así como de gestionar cuidadosamente la seguridad de los repositorios para evitar la exposición de credenciales o el uso ineficiente de recursos de almacenamiento, equilibrando así la flexibilidad de una plataforma social con el rigor técnico que exige la ingeniería de software profesional.
# Investigación: Fundamentos de Git y Flujos de Trabajo

Esta investigación cubre los conceptos esenciales para la gestión de versiones y la colaboración en proyectos de software.

---

## 1. Conceptos Clave

### 🚀 Repository (Repositorio)
Es el contenedor donde se almacena el proyecto. Contiene no solo los archivos actuales, sino todo el **historial de cambios** desde el primer día. 
*   **Local:** Ubicado en tu máquina personal.
*   **Remoto:** Alojado en plataformas como GitHub para colaboración.



### 📸 Commit (Confirmación)
Un commit es un registro de los cambios realizados. Es como guardar una partida en un videojuego; te permite volver a ese punto exacto en cualquier momento. Cada commit debe ir acompañado de un mensaje descriptivo.

### 🌿 Branch (Rama)
Es una línea de tiempo independiente. La rama principal (usualmente `main`) contiene el código estable, mientras que las ramas secundarias permiten desarrollar funciones nuevas sin romper lo que ya funciona.



### 🔃 Pull Request (PR)
Es una solicitud para fusionar los cambios de una rama a otra. Es el corazón de la colaboración, ya que permite que otros revisen tu código, sugieran cambios y aseguren la calidad antes de integrar las mejoras.

### 🍴 Fork (Bifurcación)
Es una copia completa de un repositorio ajeno en tu propia cuenta. Te permite experimentar libremente con un proyecto sin afectar el original, siendo la base del desarrollo de código abierto.

---

## 2. Comparativa Rápida

| Término | Propósito | Ámbito |
| :--- | :--- | :--- |
| **Repository** | Almacenamiento total | Proyecto |
| **Commit** | Guardado de cambios | Historial |
| **Branch** | Trabajo en paralelo | Flujo interno |
| **Pull Request** | Revisión y unión | Colaboración |
| **Fork** | Copia independiente | Propiedad |

---

## 3. Ejercicio Práctico: Manejo de Ramas

### Comandos ejecutados:
1. `git checkout -b desarrollo`: Crea y nos mueve a una nueva rama.
2. Edición del archivo `README.md`.
3. `git commit -m "Añadir sección de ejercicio práctico"`.

### Explicación de lo ocurrido con la rama principal:
Al trabajar en la rama `desarrollo`, la rama **principal** permanece en un estado "congelado" respecto a estos cambios. 

*   **Aislamiento:** Los archivos en la rama principal no contienen estas líneas de texto.
*   **Seguridad:** Si el código en `desarrollo` tuviera errores, el proyecto principal sigue funcionando perfectamente para los usuarios.
*   **Divergencia:** El historial del proyecto ahora tiene dos caminos; solo se volverán a unir cuando se realice un *Merge* o se apruebe un *Pull Request*.

---
**Elaborado por:** Eduardo  
**Institución:** CBTis 78  
**Fecha:** Mayo 2026
