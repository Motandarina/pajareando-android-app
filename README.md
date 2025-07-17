# 🦉 Pajareando
![Badge de estado](https://img.shields.io/badge/STATUS-COMPLETADO-brightgreen)
![Badge de licencia](https://img.shields.io/badge/license-MIT-blue)
![Badge de plataforma](https://img.shields.io/badge/platform-Android-green)

<div align="center">
<img src="https://raw.githubusercontent.com/Motandarina/pajareando-android-app/refs/heads/main/pajareandoApp/app/src/main/res/drawable/pajareandologo.png" alt="Pajareando Logo" width="200">

*"Descubre la biodiversidad alada de Galicia"*  
Una aplicación Android para el reconocimiento e identificación de aves
</div>

## Índice
- [Descripción del proyecto](#descripción-del-proyecto)
- [Estado del proyecto](#estado-del-proyecto)
- [Características y demostración](#características-y-demostración)
- [Acceso al proyecto](#acceso-al-proyecto)
- [Cómo abrir y ejecutar el proyecto](#cómo-abrir-y-ejecutar-el-proyecto)
- [Tecnologías utilizadas](#tecnologías-utilizadas)
- [Personas desarrolladoras del proyecto](#personas-desarrolladoras-del-proyecto)
- [Licencia](#licencia)

## Descripción del Proyecto
Pajareando es una aplicación Android nativa diseñada para amantes de las aves y la ornitología. Desarrollada como proyecto académico para la asignatura de Desarrollo de Interfaces del ciclo formativo de Desarrollo de Aplicaciones Multiplataforma (DAM), la aplicación permite a los usuarios explorar y conocer las diferentes especies de aves presentes en Galicia.

Con una interfaz intuitiva y moderna basada en Material Design 3, Pajareando ofrece una experiencia completa para descubrir la rica biodiversidad alada de la región, desde el petirrojo europeo hasta el vencejo alpino.

**🎓 Proyecto Académico** - Desarrollo de Aplicaciones Multiplataforma (DAM) - Afundación A Coruña 2024

## Estado del Proyecto
✅ **Proyecto completado y funcional** ✅

Todas las funcionalidades principales implementadas y testeadas.

## Características y Demostración
- 🔐 `Autenticación Firebase`: Sistema completo de registro y login con validación
- 🦅 `Catálogo de aves`: Base de datos con 20 especies nativas de Galicia
- ⭐ `Sistema de favoritos`: Guarda tus aves preferidas para acceso rápido
- 🎲 `Ave aleatoria`: Descubre especies de forma sorprendente
- 👤 `Gestión de perfil`: Cambio de contraseña y preferencias personales
- 🌙 `Modo oscuro`: Tema adaptable para mejor experiencia visual
- 📱 `Navegación intuitiva`: Drawer navigation con Material Design 3
- 🔄 `Datos en tiempo real`: Sincronización automática con Firebase

*"Cada ave tiene su momento perfecto para ser descubierta"*

### 📸 Capturas de pantalla

<div align="center">
  <img src="https://raw.githubusercontent.com/Motandarina/pajareando-android-app/refs/heads/main/images/screenshot/register.png" alt="Registro" width="200">
  <img src="https://raw.githubusercontent.com/Motandarina/pajareando-android-app/refs/heads/main/images/screenshot/login.png" alt="Login" width="200">
  <img src="https://raw.githubusercontent.com/Motandarina/pajareando-android-app/refs/heads/main/images/screenshot/dashboard.png" alt="Dashboard" width="200">
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/Motandarina/pajareando-android-app/refs/heads/main/images/screenshot/detalle_ave.png" alt="Detalle Ave" width="200">
  <img src="https://raw.githubusercontent.com/Motandarina/pajareando-android-app/refs/heads/main/images/screenshot/favorites.png" alt="Favoritos" width="200">
  <img src="https://raw.githubusercontent.com/Motandarina/pajareando-android-app/refs/heads/main/images/screenshot/random.png" alt="Ave Aleatorio" width="200">
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/Motandarina/pajareando-android-app/refs/heads/main/images/screenshot/profile.png" alt="Perfil" width="200">
  <img src="https://raw.githubusercontent.com/Motandarina/pajareando-android-app/refs/heads/main/images/screenshot/navigation_drawer.png" alt="Menú Navegación" width="200">
  <img src="https://raw.githubusercontent.com/Motandarina/pajareando-android-app/refs/heads/main/images/screenshot/dark_mode.png" alt="Modo Oscuro" width="200">
</div>

### Pantallas principales:
- **🔐 Login/Registro**: Autenticación segura con Firebase
- **🏠 Dashboard**: Explora el catálogo completo de aves
- **⭐ Favoritos**: Accede rápidamente a tus especies preferidas  
- **🎲 Aleatorio**: Descubre aves de forma inesperada
- **👤 Perfil**: Gestiona tu cuenta y preferencias
- **🔍 Detalle**: Información completa de cada especie
- **🌙 Modo Oscuro**: Experiencia visual adaptable

## Acceso al Proyecto
**Para acceder al código fuente:**

```bash
git clone https://github.com/Motandarina/pajareando-android-app.git
```

## Cómo abrir y ejecutar el proyecto

### Requisitos previos
- Android Studio Iguana (2023.2) o superior
- Java Development Kit 17
- Dispositivo Android con API 24+ (Android 7.0) o emulador
- 🔑 **Credenciales Firebase**: Proyecto configurado con Authentication y Realtime Database

### 🚀 Instalación y ejecución

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/Motandarina/pajareando-android-app.git
   cd pajareandoApp
   ```

2. **Abrir en Android Studio:**
   - Abrir Android Studio
   - Seleccionar "Open an existing project"
   - Navegar a la carpeta del proyecto

3. **Configurar Firebase:**
   - Añadir tu archivo `google-services.json` en `app/src/`
   - Configurar Authentication y Realtime Database en Firebase Console

4. **Sincronizar proyecto:**
   - Hacer clic en "Sync Now" cuando aparezca la notificación
   - Esperar a que se descarguen todas las dependencias

5. **Ejecutar:**
   - Conectar dispositivo Android o iniciar emulador
   - Presionar "Run" (▶️) o usar `Shift + F10`

### 🔐 Configuración Firebase necesaria

```javascript
// Estructura de datos en Firebase Realtime Database
{
  "birds": {
    "1": {
      "common_name": "European Robin",
      "scientific_name": "Erithacus rubecula",
      "description": "Pequeño paseriforme...",
      "url_photo": "https://..."
    }
  },
  "users": {
    "userId": {
      "name": "Usuario",
      "email": "usuario@email.com",
      "favorites": ["1", "2", "3"]
    }
  }
}
```

## Tecnologías utilizadas

### 🎨 Frontend Android
- **Java** - Lenguaje principal de desarrollo
- **Material Design 3** - Sistema de diseño moderno
- **Data Binding** - Enlace declarativo vista-modelo
- **Navigation Component** - Navegación entre fragmentos
- **RecyclerView** - Listas optimizadas y eficientes
- **Picasso** - Carga y cache de imágenes

### 🏗️ Arquitectura
- **MVVM** - Model-View-ViewModel pattern
- **Repository Pattern** - Abstracción de fuentes de datos
- **LiveData** - Observables lifecycle-aware
- **ViewBinding** - Acceso type-safe a vistas

### ☁️ Backend & Servicios
- **Firebase Authentication** - Gestión segura de usuarios
- **Firebase Realtime Database** - Base de datos NoSQL en tiempo real
- **Firebase Storage** - Almacenamiento de imágenes

### 🛠️ Herramientas de desarrollo
- **Android Studio** - IDE oficial
- **Gradle** - Sistema de construcción
- **Git** - Control de versiones
- **Firebase Console** - Gestión de servicios

## Personas desarrolladoras del proyecto
| Lucía Méndez Rodríguez |
| :---: |
| *Desarrolladora Android en formación* |
| *Técnico Superior en DAM* | 
| *Licenciada en Filología Hispánica* |

> *"Pajareando representa mi primera incursión seria en el desarrollo Android nativo, combinando mi interés por la naturaleza con las nuevas tecnologías."*

**📚 Contexto académico**: Proyecto de desarrollo - DAM 2024 - Centro FP Afundación A Coruña

### 🎯 Logros técnicos destacados
- Implementación del patrón MVVM
- Integración con servicios Firebase
- Gestión eficiente de estados y ciclo de vida
- Interfaz responsive con Material Design 3
- Sistema de navegación y UX

## Licencia
Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para detalles.

---
### 🌿 Inspiración
*Dedicado a la rica biodiversidad ornitológica de Galicia y a quienes se deleitan en la compañía de las aves.*

**Datos de aves**: Basado en observaciones reales de eBird y registros de biodiversidad gallega.
