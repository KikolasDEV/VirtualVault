# 📱 Virtual Vault

**Virtual Vault** es una aplicación de Flutter diseñada para proporcionar una experiencia de compra en línea sencilla y efectiva. La aplicación permite a los usuarios explorar productos, gestionar favoritos, añadir artículos al carrito y realizar pedidos. Además, incluye funcionalidades de administración para gestionar productos y ver el historial de pedidos.

## 📂 Tabla de Contenidos

1. [Características Principales](#características-principales)
2. [Tecnologías Utilizadas](#tecnologías-utilizadas)
3. [Instalación](#instalación)
4. [Uso](#uso)
5. [Estructura del Proyecto](#estructura-del-proyecto)
6. [Contribución](#contribución)
7. [Licencia](#licencia)

## 📋 Características Principales

* **Exploración de Productos**: Los usuarios pueden navegar y buscar entre una amplia gama de productos disponibles.
* **Autenticación de Usuarios**: Registro e inicio de sesión que permite a los usuarios acceder a sus favoritos, carrito de compras y realizar pedidos. Esta funcionalidad es crucial para personalizar la experiencia del usuario y gestionar sus interacciones con la aplicación.
* **Gestión de Favoritos**: Añadir y eliminar productos de la lista de favoritos para acceder fácilmente a los productos preferidos. Es necesario estar **registrado** y haber iniciado sesión para utilizar esta funcionalidad.
* **Carrito de Compras**: Añadir productos al carrito, modificar cantidades y eliminar artículos. El acceso al carrito también requiere que el usuario esté **registrado** y haya iniciado sesión.
* **Proceso de Compra**: Confirmar pedidos con un sistema de envío de correos electrónicos para la confirmación de la compra. La compra de productos sólo está disponible para usuarios **registrados** y autenticados.
* **Funcionalidades de Administrador**: Gestionar productos, incluyendo la adición, modificación y eliminación, así como la visualización del historial de pedidos. Solo accesible para usuarios con privilegios de **administrador**.
* **Modo Oscuro**: Alternar entre modo claro y oscuro para una mejor experiencia de usuario.

## 🛠️ Tecnologías Utilizadas

- **[Flutter](https://flutter.dev/)**: Framework para el desarrollo de aplicaciones multiplataforma.
- **[Dart](https://dart.dev/)**: Lenguaje de programación utilizado por Flutter.
- **[Provider](https://pub.dev/packages/provider)**: Para la gestión del estado en la aplicación.
- **[SQLite](https://pub.dev/packages/sqflite)**: Para la gestión local de bases de datos.
- **[Google Fonts](https://pub.dev/packages/google_fonts)**: Para la personalización de fuentes en la aplicación.

## 🚀 Instalación

### Requisitos Previos

- [Flutter](https://flutter.dev/docs/get-started/install) instalado en tu máquina.
- [Dart](https://dart.dev/get-dart) instalado.
- Un editor de código como [Visual Studio Code](https://code.visualstudio.com/) o [Android Studio](https://developer.android.com/studio).

### Pasos de Instalación

1. **Clonar el Repositorio**
>>git clone https://github.com/tu-usuario/virtual-vault.git
>>
>>cd virtual-vault

2. **Instalar Dependencias**
>>flutter clean
>>flutter pub get

3. **Ejecutar la Aplicación**
>>flutter run

## 🖥️ Uso

1. **Explorar Productos**
   * Inicia la aplicación para navegar por los productos disponibles. También dispone de un carrusel de imágenes de carácter decorativo con ambiente propagandístico y una barra de búsqueda de los videojuegos que se ofertan actualmente.

2. **Gestión de Favoritos**
   * **Registro/Iniciar Sesión**: Antes de añadir productos a favoritos, asegúrate de estar registrado e iniciar sesión en la aplicación.
   * Añade productos a favoritos para tener acceso rápido a ellos desde la pantalla de favoritos.

3. **Carrito de Compras**
   * **Registro/Iniciar Sesión**: Es necesario estar registrado y autenticado para añadir productos al carrito y gestionarlos.
   * Añade productos al carrito, ajusta las cantidades según sea necesario y procede con la compra.

4. **Proceso de Compra**
   * **Registro/Iniciar Sesión**: Confirma tu compra. La aplicación enviará un correo electrónico de confirmación. Solo los usuarios registrados pueden realizar compras.

5. **Modo Administrador**
   * **Registro/Iniciar Sesión**: Accede a funcionalidades de administración solo si tienes privilegios de administrador.

## 📁 Estructura del Proyecto

>>>virtual-vault/
>>>
>>>├── android/                  # Archivos específicos de Android
>>>
>>>├── assets/                   # Recursos como imágenes y fuentes
>>>
>>>├── ios/                      # Archivos específicos de iOS
>>>
>>>├── lib/                      # Código fuente principal
>>>
>>>│   ├── baseDeDatos/          # Gestión de la base de datos
>>>
>>>│   ├── models/               # Modelos de datos
>>>
>>>│   ├── screens/              # Pantallas de la aplicación
>>>
>>>│   ├── view_models/          # Gestión de estados y lógica
>>>
>>>│   └── widgets/              # Widgets reutilizables
>>>
>>>├── test/                     # Pruebas de la aplicación
>>>
>>>├── .gitignore                # Archivos y directorios a ignorar en Git
>>>
>>>├── pubspec.yaml              # Especificación de dependencias
>>>
>>>└── README.md                 # Este archivo

## 🤝 Contribución

¡Sientéte libre de apoyar el trabajo con un ⭐! Y por supuesto, si tienes sugerencias, mejoras o encuentras algún problema, por favor abre un ***issue*** o envía un ***pull request***.
Recuerda que se trata de un Trabajo Final del C.F.G.S. de DAM.

¡Gracias por tu apoyo!

