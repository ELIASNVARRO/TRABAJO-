# TRABAJO-Taller2_Prueba
Repositorio para trabajo en grupo
Estudiantes 

 
 Yhoshua Gonzalez (yhoshua21, yhoshua.gonzalez@upb.edu.co)
 Elias Navarro (eliasnvarro, elias.navarro@upb.edu.co)


informacion de un producto 
algoitmo.
Program mostrar Informacion Producto
Start
// Programa para mostrar la información sobre un producto

// Declaración de variables
Declare String nombre Producto
Declare String descripcion Producto
Declare Float precio Producto
Declare String codigo Barras

// Obtención de datos
Display "Ingrese el nombre del producto: "
Input nombre del Producto
Display "Ingrese la descripción del producto: "
Input descripcion del Producto
Display "Ingrese el precio del producto: "
Input precio del Producto
Display "Ingrese el código de barras del producto: "
Input codigo de Barras

// Presentación de información
Display "Nombre del producto: ", nombre Producto
Display "Descripción del producto: ", descripcion Producto
Display "Precio del producto: ", precio Producto
Display "Código de barras del producto: ", codigo Barras

End
pseudocodigo.
START
// Define una estructura para el producto
STRUCTURE Product
STRING name
STRING description
REAL price
INTEGER barcode
END STRUCTURE

// Create a variable to store a product
VARIABLE product: Product

// Read product information
PRINT "ingrese el nombre del producto: "
INPUT product.name

PRINT "ingrese la descripcion el producto: "
INPUT product.description

PRINT "ingrese el precio del producto: "
INPUT product.price

PRINT "Eingrese el codigo de barras: "
INPUT product.barcode

// Display the product information
PRINT "Product Information:"
PRINT "Name: " + product.name
PRINT "Description: " + product.description
PRINT "Price: " + product.price
PRINT "Barcode: " + product.barcode

END
