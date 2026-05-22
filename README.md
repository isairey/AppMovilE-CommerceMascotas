<div align="center">

<img width="220" src="https://raw.githubusercontent.com/thenifemi/PetShop/master/assets/images/PetShop-removebg.png" />

# 🐾 Pet Shop

### Aplicación móvil e-commerce para mascotas desarrollada con Flutter 🚀

<p align="center">
  <b>Pet Shop</b> es una aplicación móvil moderna desarrollada con Flutter y Firebase enfocada en comercio electrónico, autenticación segura, geolocalización y experiencia móvil responsive.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-Mobile-02569B?style=for-the-badge&logo=flutter&logoColor=white">
  <img src="https://img.shields.io/badge/Firebase-Backend-FFCA28?style=for-the-badge&logo=firebase&logoColor=black">
  <img src="https://img.shields.io/badge/Firestore-Database-FFCA28?style=for-the-badge&logo=firebase&logoColor=black">
  <img src="https://img.shields.io/badge/Google%20Places-API-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🐾 Acerca del proyecto

**Pet Shop** es una plataforma móvil de comercio electrónico para productos de mascotas construida con Flutter y Firebase. El proyecto fue diseñado para implementar características modernas de aplicaciones móviles a gran escala integrando autenticación, base de datos cloud y servicios nativos.

La aplicación incluye:

- 🔐 Autenticación de usuarios
- 🛒 Carrito de compras
- 📦 Gestión de productos
- 📍 Geolocalización
- ☁️ Firebase Cloud Firestore
- 🔔 Notificaciones
- 📱 UI responsive moderna

También implementa funcionalidades móviles avanzadas utilizando:

- Google Places API
- Firebase Authentication
- Firestore Database
- Servicios de localización
- Arquitectura Provider

---

# ✨ Características

## 🛒 Sistema E-Commerce

- 📦 Catálogo dinámico de productos
- 🛍️ Carrito de compras
- 💳 Checkout interactivo
- 📄 Vista detallada de productos
- ⚡ Actualización en tiempo real

---

## 🔐 Sistema de autenticación

- 👤 Registro de usuarios
- 🔑 Inicio de sesión
- 📧 Recuperación de contraseña
- 🔒 Firebase Authentication
- ⚡ Gestión segura de sesiones

---

## 📍 Geolocalización

- 🌍 Lectura de ubicación
- 📌 Google Places API
- 📱 Integración nativa móvil
- ⚡ Ubicación en tiempo real

---

## ☁️ Backend Firebase

- 🔥 Firebase Authentication
- ☁️ Cloud Firestore
- ⚡ Realtime Database
- 📦 Persistencia cloud
- 🔒 Seguridad integrada

---

## 🎨 Interfaz moderna

- 📱 Responsive Design
- 🌈 UI moderna
- ⚡ Animaciones fluidas
- 🎯 UX intuitiva
- 🖥️ Navegación dinámica

---

# 👨‍💻 Módulos del sistema

## 🔐 Authentication Module

Gestión de usuarios y autenticación.

### Funcionalidades

- Login
- Registro
- Logout
- Recuperación de contraseña
- Manejo de sesiones

---

## 🛒 Shopping Module

Sistema completo de compras.

### Funcionalidades

- Productos
- Carrito
- Checkout
- Pedidos
- Productos destacados

---

## 📍 Location Module

Servicios de geolocalización.

### Funcionalidades

- GPS
- Google Places
- Lectura de ubicación
- Servicios móviles

---

## ☁️ Firebase Module

Backend cloud.

### Funcionalidades

- Firestore
- FirebaseAuth
- Cloud Database
- Realtime Sync

---

# 🛠️ Tecnologías utilizadas

## 📱 Mobile Development

<p>
  <img src="https://skillicons.dev/icons?i=flutter,dart" />
</p>

- Flutter
- Dart
- Material Design
- Responsive UI

---

## ☁️ Backend & Database

<p>
  <img src="https://skillicons.dev/icons?i=firebase" />
</p>

- Firebase Authentication
- Cloud Firestore
- Firebase SDK
- Realtime Database

---

## 🌍 APIs & Services

<p>
  <img src="https://skillicons.dev/icons?i=googlecloud" />
</p>

- Google Places API
- GPS Services
- Native Mobile Features

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,androidstudio" />
</p>

- Git
- GitHub
- VS Code
- Android Studio

---

# 📂 Estructura del proyecto

```bash
AppMovilE-CommerceMascotas/
│
├── assets/
│   ├── images/
│   ├── json/
│   └── icons/
│
├── lib/
│   ├── models/
│   ├── providers/
│   ├── screens/
│   ├── services/
│   ├── widgets/
│   └── main.dart
│
├── screenshots/
├── android/
├── ios/
├── pubspec.yaml
├── README.md
└── LICENSE
```

---

# 🏗️ Arquitectura del sistema

## ⚡ Arquitectura general

```text
Flutter App → Firebase SDK → Cloud Firestore → Firebase Services
```

---

## 🔄 Flujo del sistema

```text
Usuario → Login → Productos → Carrito → Checkout → Pedido
```

---

# 📊 Funcionalidades principales

## 🔐 Login

- Inicio de sesión
- Validación de usuarios
- Manejo de sesiones
- Seguridad Firebase

---

## 🛒 Compras

- Productos dinámicos
- Carrito interactivo
- Checkout responsive
- Gestión de pedidos

---

## 📍 Ubicación

- Lectura GPS
- Google Places API
- Servicios móviles

---

## ☁️ Firebase

- Cloud Firestore
- Tiempo real
- Backend escalable
- Persistencia cloud

---

# 🔐 Seguridad

## 🛡️ Protección del sistema

- Firebase Authentication
- Gestión segura de usuarios
- Validación de formularios
- Manejo de errores
- Protección cloud

---

# ⚡ Instalación

## 📋 Requisitos

- Flutter SDK
- Firebase Project
- Android Studio / VS Code
- Emulator Android
- Google Services JSON

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/AppMovilE-CommerceMascotas.git
```

---

## 2️⃣ Entrar al proyecto

```bash
cd AppMovilE-CommerceMascotas
```

---

## 3️⃣ Instalar dependencias

```bash
flutter pub get
```

---

## 4️⃣ Configurar Firebase

Agregar archivo:

```text
google-services.json
```

Dentro de:

```text
android/app/
```

---

## 5️⃣ Configurar Firestore

Importar:

```text
foodProductsJSON/foodProducts.json
```

A Firebase Firestore.

---

## 6️⃣ Crear credenciales

Crear archivo:

```dart
credentials.dart
```

Agregar:

- Firebase API Keys
- Google Places API Key

---

## 7️⃣ Ejecutar aplicación

```bash
flutter run
```

---

# 💻 Ejemplo de autenticación

## 🔐 Login Firebase

```dart
await FirebaseAuth.instance.signInWithEmailAndPassword(
  email: email,
  password: password,
);
```

---

## 📧 Registro de usuarios

```dart
await FirebaseAuth.instance.createUserWithEmailAndPassword(
  email: email,
  password: password,
);
```

---

# 📸 Vista previa

## 📱 Interfaces de la aplicación

<div align="center">

<img src="https://raw.githubusercontent.com/thenifemi/PetShop/master/screenshots/intro.jpg" width="170"/>
<img src="https://raw.githubusercontent.com/thenifemi/PetShop/master/screenshots/signup.jpg" width="170"/>
<img src="https://raw.githubusercontent.com/thenifemi/PetShop/master/screenshots/login.jpg" width="170"/>
<img src="https://raw.githubusercontent.com/thenifemi/PetShop/master/screenshots/home.jpg" width="170"/>
<img src="https://raw.githubusercontent.com/thenifemi/PetShop/master/screenshots/productDetails.jpg" width="170"/>
<img src="https://raw.githubusercontent.com/thenifemi/PetShop/master/screenshots/cart.jpg" width="170"/>
<img src="https://raw.githubusercontent.com/thenifemi/PetShop/master/screenshots/checkout.jpg" width="170"/>
<img src="https://raw.githubusercontent.com/thenifemi/PetShop/master/screenshots/forgot.jpg" width="170"/>
<img src="https://raw.githubusercontent.com/thenifemi/PetShop/master/screenshots/notifications.jpg" width="170"/>

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y desarrollo móvil moderno

- Flutter Architecture
- Firebase Integration
- Mobile Authentication
- Cloud Database
- Responsive Mobile UI
- Native Mobile Features
- E-Commerce Apps

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 💳 Pasarela de pagos
- 🔐 Biometrics Authentication
- 📱 NFC Integration
- 🍎 iOS Version
- 🤖 AI Recommendations
- 🔔 Push Notifications
- 🌐 Multi-language support

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 🐛 Bugs & soporte

Si encuentras errores o problemas:

📧 thenifemi@gmail.com

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Flutter Mobile Developer

Desarrollador apasionado por Flutter, Firebase y aplicaciones móviles modernas 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto  

---

# 📜 Licencia

Proyecto open source orientado al aprendizaje de Flutter, Firebase y desarrollo móvil moderno.

---

<div align="center">

### 🐾 Pet Shop — Modern Flutter E-Commerce Application 🚀

</div>
