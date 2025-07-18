# 📚 Consulta de Libros desde la API de Gutendex

Este proyecto Java con Spring Boot permite consultar y analizar libros del catálogo de [Gutendex](https://gutendex.com/), una API gratuita basada en el Proyecto Gutenberg.

## 🚀 Funcionalidades

- ✅ Muestra el **top 10 de libros más descargados**.
- 🔍 Permite buscar un libro por su nombre.
- 📊 Calcula estadísticas sobre las descargas:
  - Promedio
  - Máximo
  - Mínimo
  - Total de registros evaluados

## 🛠 Tecnologías

- Java 17+
- Spring Boot
- WebClient o RestTemplate
- Jackson (para conversión JSON)
- API REST (Gutendex)

## ▶️ Cómo ejecutar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/GutierrezCesar/gutendex-books-api.git
   cd gutendex-libros

2. Asegúrate de tener configurado JDK 17 o superior.
3. Ejecuta la aplicación con:
    ./mvnw spring-boot:run
   
📌 Ejemplo de uso (consola)
```
Top 10 libros mas descargados:
PRIDE AND PREJUDICE
A CHRISTMAS CAROL
FRANKENSTEIN

Ingrese el nombre del libro que desea buscar: dracula
Libro encontrado
Título: Dracula
Autor: Bram Stoker
Descargas: 65000

Cantidad media de descargas: 35000.4
Cantidad maxima de descargas: 99000.0
Cantidad minima de descargas: 12300.0
Cantidad de registros evaluados: 32
```

