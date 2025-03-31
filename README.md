# ProductApi

Este proyecto es una API REST en .NET que gestiona productos.  
**Objetivo de la prueba técnica:**  
El entrevistado deberá identificar y corregir el siguiente bug en la lógica de negocio:

- **Regla de negocio:** Si la cantidad de un producto es **mayor a 10**, se debe aplicar un descuento del 10% sobre el total.

## Cómo Ejecutar la API

1. Clonar el repositorio.
2. Abrir el proyecto en Visual Studio o Visual Studio Code.
3. Restaurar los paquetes NuGet.
4. Ejecutar la aplicación.  
   La API se iniciará y estará disponible en `https://localhost:{puerto}`.

## Endpoints Disponibles

- **GET** `/api/products`  
  Obtiene la lista de productos.

- **GET** `/api/products/{id}`  
  Obtiene un producto por ID.

- **POST** `/api/products`  
  Crea un nuevo producto.  
  Ejemplo de JSON:
  ```json
  {
    "name": "Producto A",
    "price": 100.0,
    "quantity": 5
  }
