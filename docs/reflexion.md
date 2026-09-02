#  Reflexión — EC1 F1 A2
**Nombre:Miguel Angel Pineda Chenoweth**
**Grupo:01**

## 1. ¿Cuál es la función de Node.js en este proyecto?
Node.js nos permite ejecutar codigo dentro de la linea de comandos, transforma de texto plano a un lenguaje que la computadora entiende
y lo permite correr en la terminal
## 2. ¿Qué errores ayuda a detectar TypeScript antes de ejecutar la aplicación?
Typescript detecta cualquier error de tipado equivocado, variables que pueden ser undefined, propiedades faltantes o mal escritas, entre otras.
## 3. ¿Por qué se separaron models, data, services y utils?
Se separan para tener un código más limpio, model se encarga de almacenar la definición de atributos, data almacena datos basados en el model
services es donde va la logica de negocio y almacena las funciones y utils es para funciones genericas 
## 4. ¿Qué diferencia existe entre una función síncrona y una función async?
Las funciones sincronas se ejecutan de inicio a fin sin parar, las async se basa en promesas y pueden ser paradas en media ejecución sin bloquear
el resto del programa
## 5. ¿Por qué findTaskById devuelve Task | undefined?
Porque no hay garantia de que devuelva una task por lo cual typescript marcara error si no esta undefined
## 6. ¿Qué ventaja aporta leer APP_NAME desde process.env?
Permite cambiar esa variable de manera externa sin afectar el codigo
## 7. ¿Qué diferencia observó entre pnpm start y la secuencia pnpm build + pnpm serve?
pnpm build crea la carpeta de dist y pnpm serve ejecuta el código desde el dist, por lo cual, por ejemplo, si actualizo el código como lo
hice para agregar nuevos metodos, y no hago pnpm build y serve, el código antiguo se ejecutara
## 8. ¿Qué parte de este proyecto podrá reutilizarse cuando se construya la API con Express?
Los que más probablmente se reutilizaran son los metodos dentro de utils, ya que estos metodos son generales y no especificos a este proyecto
