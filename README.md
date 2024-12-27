# AluraGeek
![alurageekimagen](https://github.com/user-attachments/assets/7f0bc4a3-fd40-41d5-b448-44b7bb0e167c)
Este es un Challenge de Alura Latam donde se realizo una tienda virtual que gestiona productos personalizados, en este caso Pines de caricaturas.

---

## Tabla de contenidos
1. [Descripción](#descripción).
2. [Características](#características)
3. [Requisitos Previos](#requisitos-previos)
4. [Uso](#uso)
5. [Tecnologías Usadas](#tecnologías-usadas)
6. [Autor](#autor)

---

## Descripción 
PineToon es una tienda web diseñada para mostrar productos y gestionarlos de manera sencilla, el usuario puede:
- Agregar productos con nombre precio e imagen.
- Ver productos existentes
- Eliminar productos

---

## Características 
- **Interfaz amigable**: Diseñada con colores llamativos para una experiencia entretenida.
- **Gestión de productos**: Agregar y eliminar productos en tiempo real.
- **Diseño responsive**: Adaptable a cualquier tamaño de pantalla.

---

## Requisitos Previos
Antes de empezar, asegúrate de tener instalado:
- [Node.js](https://nodejs.org/) (si usas un servidor local)
- Un editor de texto como [Visual Studio Code](https://code.visualstudio.com/)
- Navegador web moderno (Chrome, Firefox, Edge)

---

## Uso
1. Agrega un producto llenando el formulario en la sección "Agregar productos".
2. Elimina un producto haciendo clic en el ícono de la papelera.
3. Los cambios se reflejarán automáticamente en la lista de productos.

---

## Tecnologías Usadas
- **HTML5**: Para la estructura de la página.
- **CSS3**: Para el diseño y estilo visual.
- **JavaScript**: Para la funcionalidad dinámica.
- **Node.js**(opcional): Para el servidor local.
- **[MockAPI.io](https://mockapi.io)**: Para simular una API y gestionar los datos del proyecto.

---

## Descripción del Servidor MockAPI.io
Este proyecto utiliza [MockAPI.io](https://mockapi.io) como backend para almacenar y gestionar los datos de los productos. MockAPI proporciona un servidor externo que permite realizar operaciones **CRUD** (Crear, Leer, Actualizar, Eliminar) de forma sencilla a través de una API REST.

### Endpoints Utilizados
Los siguientes endpoints fueron configurados en MockAPI para interactuar con los datos:

1. **Obtener todos los productos**  
   `GET https://mockapi.io/endpoint/products`

2. **Agregar un producto**  
   `POST https://mockapi.io/endpoint/products`  
   - **Body ejemplo**:
     ```json
     {
       "name": "Nuevo Producto",
       "price": 50,
       "image": "url-de-la-imagen"
     }
     ```

3. **Eliminar un producto**  
   `DELETE https://mockapi.io/endpoint/products/:id`

---

## Autor
Desarrollado por Camila Perdomo

   

