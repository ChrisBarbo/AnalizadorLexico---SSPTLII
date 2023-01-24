# AnalizadorLexico---SSPTLII
Analizador lexico completo - Garcia Barbosa Christian

En esta practica, debemos crear un analizador lexico completo donde se muestre el simbolo acompañado del tipo y esto de acuerdo al pdf que nos proporciono el profesor.
A diferencia del mini analizador no utilice listas, con la finalidad de mostrar los tokens de forma mas clara. 
Ademas, hice uso de subcadenas, cosa que aprendi y que me gusto su forma facil de implementacion 

Para iniciar defini la funcion lexer, que recibe la cadena ingresada, tambien se inicializa una variable para recorrer la cadena y entra en un while donde sea menor que la cantidad total de caracteres

![image](https://user-images.githubusercontent.com/104050689/214213561-e65c388e-53ea-4bed-863e-68fcb1f5f874.png)

Luego, de acuerdo al pdf. Tenemos palabras reservaas, las cuales decidi definir al inicio del codigo. 
![image](https://user-images.githubusercontent.com/104050689/214213912-69077fb9-25b3-4fec-9262-494bcd0b32ed.png)

El uso de las subcadenas, hace el conteo de los caracteres de acuerdo a la posicion que le indiquemos esto segun la longitud de la cadena. Por lo que en este caso va a depender de cual sea la longitud de cada palabra reservada

Como se ve, en su mayoria hice uso de condicionales 'Elif' para definir cada posible caso. Ahora hice lo mismo, pero ahora con los tipos de dato, que en este caso serian int, float, void

![image](https://user-images.githubusercontent.com/104050689/214214261-cbeb2363-34fd-4764-9da8-329494a3288d.png)

Replique los casos que se utilizaron en el mini analizador, pero ahora sin variables temporales y cambiando la manera de impresion:

![image](https://user-images.githubusercontent.com/104050689/214214525-b41cc762-ef1f-4ed5-9c04-ed6437beb84e.png)

Asi sucesivamente y basandome en la tabla del pdf. Otro ejemplo es la implementacion de los operadores. De suma, multiplicacion 
![image](https://user-images.githubusercontent.com/104050689/214214694-2e92bcd6-309a-4d41-9cc6-40a42d1c4ef6.png)

Luego, para los operadores de igualdad y relacionales fue la parte donde mas se me dificulto ya que, por ejemplo, "==" de la primer forma en que lo realize siempre lo detectaba como doble asignacion. Cuando yo buscaba que fuera Operdor de igualdad. Y de igual forma con los operadores relacionales. Por lo que implemente en parte las subcadenas pero ahora definiendo los caracteres segun el caso 

![image](https://user-images.githubusercontent.com/104050689/214215039-01afca45-58b0-42bf-a8f2-7a486f0282ef.png)

Y asi fue que implemente los demas simbolos que se piden en el pdf. 

![image](https://user-images.githubusercontent.com/104050689/214215150-9659ce7c-95b0-40d4-b1d2-032619f48c20.png)

Para el caso de los parentesis tambien hice algunas modificaciones de acuerdo a lo que habia codificado primero. Ya que, estos en el pdf cada parentesis tiene un tipo, por lo que tuve que hacer una condicion por parentesis y a cada una agregarle el tipo. Cosa que tambien fue necesario hacer con las llaves:

![image](https://user-images.githubusercontent.com/104050689/214215510-dccbf388-b876-4756-b196-b0e697ee589d.png)

Por ultimo, en el main tambien hice algo como en el mini analizador. Solicitando al usuario una cadena y haciendo un pequeño menu.

![image](https://user-images.githubusercontent.com/104050689/214215692-f62165b4-90ab-4028-920d-72da793b4069.png)

Resultados:

Para muestra de todos los simbolos los ingrese como cadena, y eso es lo que muestra la salida.

![image](https://user-images.githubusercontent.com/104050689/214215814-bfc5f5e8-e895-42f0-bcf8-6aa479886b73.png)





