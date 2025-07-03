# AppParcialCM - Sistema de Gestión de Comida Rápida

## Descripción
Aplicación Android para gestión de ventas, productos, inventario y clientes en un negocio de comida rápida.

## Características
- ✅ Sistema de autenticación con SQLite
- ✅ Registro de usuarios
- ✅ Recuperación de contraseña
- ✅ Dashboard con módulos principales
- ✅ Gestión de ventas
- ✅ Gestión de productos
- ✅ Control de inventario
- ✅ Gestión de clientes
- ✅ Reportes y estadísticas
- ✅ Configuración del sistema

## Credenciales de Acceso

### Usuario de Prueba (Creado Automáticamente)
- **Usuario:** `admin`
- **Contraseña:** `123456`

### Cómo Registrar un Nuevo Usuario
1. Abrir la aplicación
2. Tocar "Registrarse"
3. Completar todos los campos requeridos
4. Tocar "Registrarse"

## Instalación y Uso

### Requisitos
- Android 7.0 (API 24) o superior
- 50MB de espacio libre

### Instalación
1. Descargar el archivo APK
2. Habilitar "Instalar aplicaciones de fuentes desconocidas"
3. Instalar la aplicación
4. Abrir la aplicación

### Primer Acceso
1. Usar las credenciales de prueba: `admin` / `123456`
2. O registrar un nuevo usuario
3. Acceder al dashboard principal

## Solución de Problemas

### La aplicación no se abre
1. Verificar que Android 7.0 o superior
2. Reinstalar la aplicación
3. Limpiar datos de la aplicación

### Error de login
1. Verificar credenciales correctas
2. Usar usuario de prueba: `admin` / `123456`
3. Registrar nuevo usuario si es necesario

### La aplicación se cierra inesperadamente
1. Reiniciar el dispositivo
2. Desinstalar y reinstalar la aplicación
3. Verificar espacio disponible en el dispositivo

## Estructura del Proyecto

```
app/src/main/java/com/example/appparcialcm/
├── LoginActivity.kt              # Pantalla de login
├── RegistrationActivity.kt       # Registro y perfil de usuario
├── ForgotPasswordActivity.kt     # Recuperación de contraseña
├── DashboardActivity.kt          # Dashboard principal
├── SalesActivity.kt              # Gestión de ventas
├── ProductsActivity.kt           # Gestión de productos
├── InventoryActivity.kt          # Control de inventario
├── CustomersActivity.kt          # Gestión de clientes
├── ReportsActivity.kt            # Reportes y estadísticas
├── SettingsActivity.kt           # Configuración
├── DatabaseHelper.kt             # Gestión de base de datos SQLite
└── Adapters/                     # Adaptadores para RecyclerViews
```

## Tecnologías Utilizadas
- **Lenguaje:** Kotlin
- **Base de Datos:** SQLite
- **UI:** Material Design 3
- **Arquitectura:** ViewBinding
- **Navegación:** Intents

## Desarrollo

### Compilar el Proyecto
```bash
./gradlew assembleDebug
```

### Instalar en Dispositivo
```bash
./gradlew installDebug
```

### Limpiar Proyecto
```bash
./gradlew clean
```

## Contacto
Para soporte técnico o reportar problemas, contactar al desarrollador.

---
**Versión:** 1.0  
**Fecha:** 2024 