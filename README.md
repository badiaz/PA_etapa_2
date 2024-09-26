# Fake Store API Proyecto etapa 2 del reto Pragma Academy

Este proyecto es una apliación de consola en Dart que interactúa con la [Fake Store API](https://fakestoreapi.com/). La aplicación permite obtener productos, categorías y usuarios de la tienda simulada, utilizando solicitudes HTTP. También incluye funciones para mostrar los datos en la consola de manera detallada y en formato de tabla.

## Características

- Obtener una lista de productos desde la API.
- Obtener una lista de categorías de productos.
- Obtener una lista de usuarios.
- Mostrar productos, categorías y usuarios en la consola en formato extendido o tabular.
- Manejo de errores y respuestas con la estructura `Either` de la biblioteca `dartz`.

## Dependencias

Este proyecto utiliza las siguientes dependencias:

1. **http**: Para realizar solicitudes HTTP.
2. **dartz**: Para manejar errores y respuestas con la estructura `Either`.

## Estructura del proyecto
📦fake_store_api
 ┣ 📂lib
 ┃ ┣ 📂classes
 ┃ ┃ ┣ 📜address.dart            # Define la clase Address y Geolocation
 ┃ ┃ ┣ 📜category.dart           # Define la clase Category
 ┃ ┃ ┣ 📜name.dart               # Define la clase Name
 ┃ ┃ ┣ 📜product.dart            # Define la clase Product
 ┃ ┃ ┣ 📜user.dart               # Define la clase User
 ┃ ┣ 📂print_functions
 ┃ ┃ ┣ 📜print_categories.dart   # Funciones para imprimir categorías en consola
 ┃ ┃ ┣ 📜print_products.dart     # Funciones para imprimir productos en consola
 ┃ ┃ ┣ 📜print_users.dart        # Funciones para imprimir usuarios en consola
 ┃ ┗ 📜fake_store_api.dart       # Funciones para interactuar con la API (productos, categorías, usuarios)
 ┣ 📂bin
 ┃ ┗ 📜main.dart                 # Punto de entrada principal donde se ejecutan las funciones de la API

## Como ejecutar el proyecto
- Navegue a la carpeta /bin y una vez ahí ejecute dart run .\main.dart