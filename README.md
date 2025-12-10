# 🎓 PUC Chile | Generador de Objetivos SMART de Desempeño [MVP]

## 🎯 Descripción del Proyecto

Esta aplicación web es el MVP de una herramienta diseñada para facilitar el proceso de definición de **Objetivos S.M.A.R.T.** (Específicos, Medibles, Alcanzables, Relevantes y con Plazo Temporal) para las evaluaciones de desempeño del personal de la Pontificia Universidad Católica de Chile.

La herramienta guía al evaluador a través de un flujo sencillo:

1.  Selección del **Perfil de Cargo** (Misión y Competencias).
2.  Alineación con los **Objetivos Estratégicos** del Plan de Desarrollo Estratégico (PDE) de la Universidad.
3.  Uso de un **Constructor asistido** que genera automáticamente una frase coherente y profesional que cumple con la metodología SMART.

### Características Clave:

* **Front-end Only (Estático):** No requiere base de datos ni servidor complejo. Es rápido, seguro y fácil de mantener.
* **Resultados Copiables:** Genera una frase que se puede copiar con un solo clic para usar en el sistema de gestión de desempeño.

---

## 🛠️ Stack Tecnológico

La aplicación es un sitio de una sola página (SPA) que se ejecuta enteramente en el navegador.

* **Framework Principal:** React.js (con Vite)
* **Estilado:** Tailwind CSS v4 (para un diseño limpio e institucional)
* **Datos:** Un archivo local de configuración (`data.json`) que actúa como base de datos de perfiles y objetivos.
* **Hosting:** GitHub Pages (o ambiente estático interno).

---

## ⚙️ Configuración y Ejecución Local

Para levantar el proyecto en tu entorno de desarrollo:

1.  **Clonar el repositorio:**
    ```bash
    git clone git@github.com:Rydozz15/smart-objectives.git
    cd puc-smart-goals
    ```

2.  **Instalar dependencias:**
    ```bash
    npm install
    ```

3.  **Ejecutar en modo desarrollo:**
    ```bash
    npm run dev
    ```
    La aplicación estará disponible en `http://localhost:5173/` (o el puerto que indique Vite).

---

## ➡️ Próximos Pasos & Tareas Pendientes

La estructura lógica de la aplicación ya está definida y funcionando. Las siguientes tareas se enfocan en contenido y funcionalidad para el lanzamiento:

1.  **Carga de Datos Reales (El Cerebro):**
    * Completar el archivo de configuración con los **25 (o más) Perfiles de Cargo** oficiales de la PUC (Misión, Responsabilidades y Competencias).
    * Asegurar que los **Objetivos Estratégicos** listados sean los actuales del Plan de Desarrollo vigente.

2.  **Funcionalidad de Lista (Mejora UX):**
    * Implementar la capacidad de **guardar y agregar múltiples objetivos** (Objetivo 1, Objetivo 2, etc.) antes de copiarlos en un formato de lista final.

3.  **Refinamiento de la Plantilla SMART:**
    * Revisar y ajustar la plantilla de redacción generada para asegurar que el lenguaje sea formal y cumpla estrictamente con los estándares de la Universidad.

4.  **Testing y Despliegue Final:**
    * Realizar pruebas de usabilidad con evaluadores de desempeño.
    * Asegurar el despliegue estable en el entorno final de producción.

---

El objetivo de esto es ser una prueba de concepto, ya que falta aún validación con usuarios, expertos e integración con datos reales.