<!DOCTYPE html>
<html>
<head>
  <title>Tienda de E-commerce</title>
  <style>
    /* Estilos CSS básicos */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    
    header {
      background-color: #333;
      color: #fff;
      padding: 10px;
      text-align: center;
    }
    
    main {
      padding: 20px;
    }
    
    footer {
      background-color: #333;
      color: #fff;
      padding: 10px;
      text-align: center;
    }
    
    .product {
      border: 1px solid #ccc;
      padding: 10px;
      margin-bottom: 20px;
      width: 300px;
      float: left;
      margin-right: 20px;
    }
    
    .product img {
      width: 100%;
      max-height: 200px;
      object-fit: cover;
      margin-bottom: 10px;
    }
    
    .product h3 {
      margin: 0;
    }
    
    .product p {
      margin: 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Tienda de E-commerce</h1>
  </header>
  
  <main>
    <div class="product">
      <img src="producto1.jpg" alt="Producto 1">
      <h3>Producto 1</h3>
      <p>Precio: $19.99</p>
      <button>Agregar al carrito</button>
    </div>
    
    <div class="product">
      <img src="producto2.jpg" alt="Producto 2">
      <h3>Producto 2</h3>
      <p>Precio: $29.99</p>
      <button>Agregar al carrito</button>
    </div>
    
    <!-- Agrega más productos aquí -->
    
  </main>
  
  <footer>
    <p>Todos los derechos reservados &copy; 2023</p>
  </footer>
</body>
</html>
