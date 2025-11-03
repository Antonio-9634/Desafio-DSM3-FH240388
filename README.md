# AprendeUDBApp 📚 (Proyecto DSM — UDB 2025)

**Aplicación Android** desarrollada en **Kotlin** (modo oscuro, Material Design) para el Tercer Desafío Práctico de *Desarrollo de Software para Móviles* — Universidad Don Bosco.

---

## ✅ Resumen
AprendeUDBApp permite a los estudiantes:
- Registrarse e iniciar sesión (validación de contraseña fuerte).
- Ver una lista de recursos de aprendizaje (libros, videos, tutoriales).
- Buscar, agregar, editar y eliminar recursos (CRUD) consumiendo una **API externa (MockAPI.io)**.
- Interfaz en **modo oscuro**, feedback visual con toasts, diálogos y loaders.

---

## 🔧 Tecnologías
- Android Studio
- Kotlin
- Material Design (modo oscuro)
- Retrofit2 + Gson
- OkHttp Logging
- Glide (carga de imágenes)
- RecyclerView + SwipeRefreshLayout

---

## 📁 Estructura del proyecto (resumen)

AprendeUDBApp/

├─ app/

│ ├─ src/main/java/com/example/aprendeudbapp/

│ │ ├─ data/

│ │ │ ├─ api/ (ApiService.kt)

│ │ │ ├─ model/ (Resource.kt)

│ │ │ └─ repository/ (ResourceRepository.kt)

│ │ ├─ ui/

│ │ │ ├─ login/ (LoginActivity.kt)

│ │ │ ├─ register/ (RegisterActivity.kt)

│ │ │ ├─ main/ (MainActivity.kt)
│ │ │ └─ adapter/ (ResourceAdapter.kt)
│ │ └─ utils/ (ValidationUtils.kt)
│ └─ res/ (layouts, values, drawables)
└─ README.md
