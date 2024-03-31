

ESTRUCTURA DE DATOS ACTIVIDAD #1  


 

Declarar y definir arreglos
 1.1 Declarar un arreglo para cada tipo de dato.

     

      //Arreglo de enteros
        int[] arregloInt = new int[5];
        arregloInt[0] = 2;
        arregloInt[1] = 8;
        arregloInt[2] = 4;
        arregloInt[3] = 22;
        arregloInt[4] = 2147483647;//Limite maximo que se puede almacenar en una variable int

        //Arreglo de double
        double[] arregloDouble = new double[5];
        arregloDouble[0] = 1.1;
        arregloDouble[1] = 0.5;
        arregloDouble[2] = 1.5;
        arregloDouble[3] = 20.5;
        arregloDouble[4] = 5.5;

        //Arreglo de String
        String[] arregloString = new String[5];
        arregloString[0] = "Daniel";
        arregloString[1] = "Juan";
        arregloString[2] = "Diego";
        arregloString[3] = "Anuel";
        arregloString[4] = "Arcangel";

        //Arreglo de float
        float[] arregloFloat = new float[5];
        arregloFloat[0] = 11.33f;
        arregloFloat[1] = 33.33f;
        arregloFloat[2] = 10.40f;
        arregloFloat[3] = 1.3f;
        arregloFloat[4] = 3.16f;

        //Arreglo de byte
        byte[] arregloByte = new byte[5];
        arregloByte[0] = 1;
        arregloByte[1] = 2;
        arregloByte[2] = 4;
        arregloByte[3] = 127;//Limite maximo que se puede almacenar en una variable byte
        arregloByte[4] = 2;

        //Arreglo de Long
        long[] arregloLong = new long[5];
        arregloLong[0] = 2929L;
        arregloLong[1] = 11111L;
        arregloLong[2] = 444L;
        arregloLong[3] = 922337255L;
        arregloLong[4] = 2992L;

        //Arreglo de Caracteres
        char[] arregloChar = new char[5];
        arregloChar[0] = 'A';
        arregloChar[1] = 'E';
        arregloChar[2] = 'I';
        arregloChar[3] = 'O';
        arregloChar[4] = 'U';

        //Arreglo de short
        short[] arregloShort = new short[5];
        arregloShort[0] = 0;
        arregloShort[1] = 11;
        arregloShort[2] = 3;
        arregloShort[3] = 32767;//Limite maximo que se puede almacenar en una variable short
        arregloShort[4] = 5;

        //Arreglo de tipo Objeto
        Object[] arregloObjects = new Object[5];
        arregloObjects[0] = ("Luciano");
        arregloObjects[1] = (23);
        arregloObjects[2] = ('J');
        arregloObjects[3] = (4.3f);
        arregloObjects[4] = (true);

 

 

 

R// Los arreglos se inicializan y se les asigna el rango o tamaño del arreglo, luego se asigna un valor correspondiente al tipo de dato en un índice del arreglo comenzando desde cero hasta llegar al rango –1. 

 


1.2 Mostrar los valores de cada arreglo 

 
      //Bucle for para imprimir los elementos que componen los arreglos 
        System.out.println("Arreglo de int");
        
        for (byte i = 0; i < arregloInt.length; i++) {
            System.out.print(arregloInt[i]);

            if (i < arregloInt.length - 1) {
                System.out.print(", ");

            }

        }
        System.out.println(" ");
        System.out.println(" ");

        System.out.println("Arreglo de byte");
        for (byte i = 0; i < arregloByte.length; i++) {

            System.out.print(arregloByte[i]);
            if (i < arregloByte.length - 1) {
                System.out.print(", ");

            }
        }
        System.out.println(" ");
        System.out.println(" ");

        System.out.println("Arreglo de char");
        for (byte i = 0; i < arregloChar.length; i++) {

            System.out.print(arregloChar[i]);
            if (i < arregloChar.length - 1) {
                System.out.print(", ");

            }
        }
        System.out.println(" ");
        System.out.println(" ");
        System.out.println("Arreglo de double");
        for (byte i = 0; i < arregloDouble.length; i++) {

            System.out.print(arregloDouble[i]);
            if (i < arregloDouble.length - 1) {
                System.out.print(", ");

            }
        }
        System.out.println(" ");
        System.out.println(" ");
        System.out.println("Arreglo de short");

        for (byte i = 0; i < arregloShort.length; i++) {

            System.out.print(arregloShort[i]);
            if (i < arregloShort.length - 1) {
                System.out.print(", ");

            }
        }
        System.out.println(" ");
        System.out.println(" ");
        System.out.println("Arreglo de float");
        for (byte i = 0; i < arregloFloat.length; i++) {

            System.out.print(arregloFloat[i]);
            if (i < arregloFloat.length - 1) {
                System.out.print(", ");

            }
        }
        System.out.println(" ");
        System.out.println(" ");
        System.out.println("Arreglo de long");

        for (byte i = 0; i < arregloLong.length; i++) {

            System.out.print(arregloLong[i]);
            if (i < arregloLong.length - 1) {
                System.out.print(", ");

            }
        }
        System.out.println(" ");
        System.out.println(" ");
        System.out.println("Arreglo de String");

        for (byte i = 0; i < arregloString.length; i++) {

            System.out.print(arregloString[i]);
            if (i < arregloString.length - 1) {
                System.out.print(", ");

            }
        }
        System.out.println(" ");
        System.out.println(" ");

        System.out.println("Arreglo de Objetos");
        for (byte i = 0; i < arregloObjects.length; i++) {

            System.out.print(arregloObjects[i]);
            if (i < arregloObjects.length - 1) {
                System.out.print(", ");

            }

        }

R// Se usa el bucle for o for-each para recorrer el arreglo deseado, se le asigna el valor recien creado de la sentencia for al indice del arreglo y se imprime el dato dependiendo donde se encuentre el indice en el arreglo. Este mismo codigo se puede usar para imprimir los valores de los diferentes arreglos que hay. 

  

 

1.3 Declarar un arreglo llamado dataStructs de tipo String y asignar los elementos (listas, colas, pilas, mapas y conjuntos) con la sintaxis de llaves 

        //Arreglo dataStructs de tipo String
        String[] dataStructs = {
            "Listas", //0
            "Colas", //1
            "Pilas", //2
            "Mapas", //3
            "Conjuntos" //4
        };
 

R// Se crea un arreglo llamado dataStructs, el rango de este arreglo esta dado por la cantidad de elementos que tenga  

 

 

1.4 Declarar un arreglo llamado características de tipo String y rellenar el arreglo con los datos (simples, circulares y enlazadas - primero en entrar, primero en salir. Ultimo en entrar, primero en salir primero en entrar, ultimo en salir – parejas de clave y valor – elementos no repetidos) ingresados por teclado. 


    String[] caracteristicas = new String[5]; //Se crea un arreglo de tipo string 
    
     public static void datosPorteclado(String[] dataStructs, String[] caracteristicas, Scanner teclado) {
        //Solicito ingreso de datos por teclado
        System.out.println("Ingresar los siguientes datos por teclado:\n"
                + "1. Simples, Circulares y Enlazadas\n"
                + "2. Primero en entrar, Primero en Salir. Ultimo en entrar, Primero en salir\n"
                + "3. Primero en entrar, Ultimo en salir\n"
                + "4. Parejas de clave y valor\n"
                + "5. Elementos no repetidos");

        //Bucle for para recorrer el arreglo 
        for (byte i = 0; i < caracteristicas.length; i++) {
            //Se le asigna al arreglo los elementos que se van ingresando por teclado hasta llenar el rango del arreglo
            caracteristicas[i] = teclado.nextLine();
        }
        //Bucle for para recorrer el arreglo e imprimir los arreglos dataStruct y caracteristicas
        for (byte i = 0; i < caracteristicas.length; i++) {

            System.out.print(dataStructs[i] + ": ");
            System.out.println(caracteristicas[i]);
        }
    }



 

R// Se llama la función Scanner para que pueda leer los datos que se ingresen por teclado, luego se inicializa el arreglo características de tipo String con un rango de 5. Se crea una función para organizar mejor el código que pida los datos por teclado e indique que datos debe ingresar para así poder almacenarlos en el arreglo, esta función recibe como parámetros los 2 arreglos y la variable teclado de tipo Scanner inicializada en el método main.  Cuando se llena el arreglo caracteristicas con los datos ingresados se crea un bucle for para recorrer el arreglo caracteristicas y se le asigna la variable del bucle for al índice de los 2 arreglos para que cuando se impriman cada elemento de los arreglos queden concatenados con su respectivo elemento. 
    Manipular elementos dentro de arreglos  


   2.1 Declarar un arreglo de enteros llamado ventas, inicializar el arreglo con una cantidad aleatoria de elementos, llenar el arreglo con valores aleatorios entre 1 y 1000, mostrar la cantidad de ventas, mostrar el valor de cada una de las ventas, mostrar el valor de cada una de las ventas, mostrar el total de ventas y mostrar el promedio de las ventas. 

    //Variable con numero aleatorio
        int aleatorio = (int) (Math.random() * 20) + 5;
        int[] ventas = new int[aleatorio]; //Arreglo ventas con rango aleatorio     
        int suma = 0; //Variable para sumar la cantidad de ventas 
        float promedio; //Variable para calcular el promedio de las ventas

        //Bucle for para recorrer el arreglo ventas
        for (int i = 0; i < ventas.length; i++) {
            int random = (int) (Math.random() * 1000)+1; //Variable con numeros aleatorios del 1 al 1000

            ventas[i] = random;
            suma = random + suma;//La variable suma es igual al dato almacenado mas 0 
            //Se imprimen los valores del arreglo con con su posicion
            System.out.println("El valor de la venta N° " + (i + 1) + " es igual a: " + random + " $");

        }
        System.out.println(" ");

        System.out.println("-La cantidad de ventas fueron: " + ventas.length);
        System.out.println("-Las cantidad de ventas totales es de: " + suma);
        promedio = (float)suma / ventas.length;//Se calcula el promedio 
        System.out.println("-El promedio de las ventas es: " + promedio);
 

R//Se crea una variable llamada aleatorio para almacenar un numero al azar entre 5 y 20 que será el rango del arreglo ventas, luego se crean una variable suma de tipo int para calcular la suma de todas las ventas y una variable promedio para sacar el promedio de las ventas. Se crea un bucle for para recorrer el arreglo ventas, dentro de este bucle se crea una variable int llamada random para que almacenar un valor aleatorio de 1 a 1000 cada vez que se reinicia el bucle (la función Math.random() elige un numero aleatorio dentro del rango que se le asigne que en este caso es 1000, el (int) es para que devuelva un int y no un double), en el índice en el que se encuentre el bucle almacenar el valor aleatorio en el arreglo, la variable suma será igual a ese mismo valor almacenado + 0 y se imprime la posición junto con el valor recién almacenado, así continua el  bucle hasta llenar la longitud del arreglo. Cuando termina el bucle se imprime la cantidad de ventas que es igual a la longitud del arreglo, la suma que es el acumulado de todos los números ingresados al arreglo, el promedio se calcula sacando la suma de todas las ventas dividido por las ventas realizadas que en este caso es el tamaño del arreglo ((float)suma /ventas.lenght devuelve un valor float para que sea lo más acercado al promedio) y se imprime el resultado. 

 
 

Buscar un elemento en un arreglo 
3.1 Diseñar una función que permita buscar la venta más alta e invocar 

     public static int ventaMax(int[] ventas) {

        int valorMax = Integer.MIN_VALUE;
        for (byte i = 0; i < ventas.length; i++) {
            if (ventas[i] > valorMax) {

                valorMax = ventas[i];
            }

        }

        return valorMax;
    }

 

 

R// Se crea una función pública estática que devuelva un entero llamada ventaMax que recibe como parámetros el arreglo ventas de tipo int, se crea una variable de tipo int llamada valorMax para almacenar el valor mínimo de un entero para poder encontrar el valor de la venta más alta,  el bucle for para recorrer el arreglo y se crea un  condicional if que compara el valor de la venta en el índice en el que se encuentra el bucle es mayor al valorMax y le da el valor de la venta en ese índice al valorMax y el índice aumenta, si no se cumple la condición entonces el bucle no ejecuta el if y al finalizar el bucle retorna el valorMax con la venta más alta. 

 

  3.2 Diseñar una función que permita buscar la venta mas baja. 

     public static int ventaMin(int[] ventas) {
        int valorMin = Integer.MAX_VALUE;

        for (byte i = 0; i < ventas.length; i++) {
            if (ventas[i] < valorMin) {
                valorMin = ventas[i];
            }
        }

        return valorMin;
    }
 

R//Se crea una función llamada ventaMin que devuelva un entero y que reciba como parámetros el arreglo ventas, como en la función anterior se crea una variable int con el valor máximo de un entero, un bucle for para recorrer el arreglo y un condicional, pero en este caso la condición es que la venta en esa posición sea menor a valorMin y si se cumple la condicion el valorMin pasa a tener el valor de la venta en esa posición. 

 

3.3 Diseñar una función que permita obtener el total de las ventas en invocarla 

 public static int cantidadVentas(int[] ventas) {

        int sumaTot = 0;
        for (byte i = 0; i < ventas.length; i++) {

            sumaTot = sumaTot + ventas[i];

        }
        return sumaTot;
    }

R// Se crea una función denominada cantidadVentas que devuelve un int y recibe como parámetros el arreglo ventas, en esta función se crea una variable sumaTot con el valor de 0 y un for para recorrer el arreglo, dentro del bucle for sumaTot pasa a ser igual a la venta + 0 para no alterar el valor y al finalizar el bucle se devuelve el valor de sumaTot. 

 

3.4 Diseñar una función que permita obtener el promedio de las ventas. 


    public static float proVentas(int[] ventas) {
        float promeVen;
        int sumass = 0;
        for (byte i = 0; i < ventas.length; i++) {

            sumass = ventas[i] + sumass;

        }
        promeVen = (float)sumass / ventas.length;
        return promeVen;
    }

 

R//Se crea una función de nombre proVentas que devuelve un valor de tipo float y que recibe como parámetro el arreglo ventas, en la función proVentas se crea una variable float llamada promeVen para guardar el promedio de las ventas y una variable suma, dentro del bucle for se hace el mismo procedimiento de la función cantidadVentas para calcular la suma total de las ventas. Al finalizar el bucle se calcula el promedio de las ventas dividiendo la suma total de las ventas entre la cantidad de ventas que es la longitud del arreglo y se devuelve el valor de promeVen. 

 

3.5 Diseñar una función que devuelva la venta cuyo valor se acerque más al valor que le sigue al promedio. 


    public static int valorPosPromedio(int[] ventas) {
        float promeVen = proVentas(ventas);
        int valorPosPro = ventas[0];
        float diferencia = Math.abs(ventas[0] - promeVen);

        for (byte i = 0; i < ventas.length; i++) {
            if (Math.abs(ventas[i] - promeVen) < diferencia) {
                valorPosPro = ventas[i];
                diferencia = Math.abs(ventas[i] - promeVen);
            }
        }
        return valorPosPro;
    }

 

R// Se crea una función que devuelva un int y que reciba como parámetro el arreglo ventas, en esta función se crea una variable float promeVen a la que se le asigna el valor de la función proVentas, una variable int valorPosPro para encontrar el valor que le sigue al promedio y una variable float diferencia que se le asigna el valor absoluto de la venta en la posición del arreglo menos el promedio de las ventas. En el bucle for se crea un if con la condicion de que el valor absoluto de la venta en una posición menos el promedio sea menor a la diferencia, si la condicion se cumple entonces el valor de valorPosPro pasa a ser la venta en la posición del índice y la diferencia pasa a ser el valor absoluto de esa venta en la posición del índice menos el promedio de las ventas.  

 

 

 

Ordenar arreglos 
 4.1 Diseñar una función que permita ordenar las ventas de forma descendente 


     public static void ordenarDescendente(int[] ventas) {
        int index ;
        for (int i = 0; i < ventas.length - 1; i++) {

            for (int j = i + 1; j < ventas.length; j++) {
                if (ventas[i] < ventas[j]) {
                    index = ventas[i];
                    ventas[i] = ventas[j];
                    ventas[j] = index;
                }
            }
        }
        System.out.println("Ventas ordenadas de forma descendente");
        for (byte i = 0; i < ventas.length; i++) {
            System.out.println(ventas[i]);
        }
    }

     

 

R// Se crea una función que no devuelve ningún valor y que recibe como parámetro el arreglo ventas, dentro de la función se crea una variable int llamada index para que sirve de guía, para ordenar este arreglo se usa el algoritmo de ordenamiento de burbuja el cual está formado por dos bucles, el externo y el interno. El bucle externo recorre el arreglo desde la posición 0 hasta la penúltima posición del arreglo, el bucle interno recorre el arreglo desde la posición del bucle anterior mas uno para facilitar la comparación de los valores hasta llegar al rango de arreglo. Dentro del bucle interno se crea un if con la condicion de que, si la venta en el índice i es mayor a la venta en el índice j, index pasa a guardar el valor de la venta en el índice i, la venta en el índice i guarda el valor de la venta en el índice j y la venta en el índice j pasa a tener el valor de index. Al finalizar estos bucles se muestra un anuncio informando el orden del arreglo y se crea un bucle for para imprimir el arreglo.  

 

4.2 Diseñar una función que permita ordenar las ventas de forma ascendente  


     public static void ordenarAscendente(int[] ventas) {
        int index;
        for (int i = 0; i < ventas.length - 1; i++) {

            for (int j = i + 1; j < ventas.length; j++) {
                if (ventas[i] > ventas[j]) {
                    index = ventas[i];
                    ventas[i] = ventas[j];
                    ventas[j] = index;
                }
            }
        }
        System.out.println("Ventas ordenadas de forma Ascendente");
        for (byte i = 0; i < ventas.length; i++) {
            System.out.println(ventas[i]);
        }
    }

R//En este caso se reutiliza el código y se crea una función similar a la anterior con la única diferencia que en el if la condicion se invierte pasando de menor que a mayor que. 

 

4.3 Diseñar una función que permita desordenar las ventas  

       public static void desordenarVentas(int[] ventas) {
        for (byte i = 0; i < ventas.length; i++) {
            int randomPosition = (int) Math.random() * ventas.length;
            int index = ventas[i];
            ventas[i] = ventas[randomPosition];
            ventas[randomPosition] = index;
        }
        System.out.println("Ventas desordenadas");
        for (byte i = 0; i < ventas.length; i++) {
            System.out.println(ventas[i]);
        }
    }
 

 

R// Se crea una función que no devuelve ningún valor y recibe como parámetro el arreglo ventas. Dentro de esta función se encuentra un bucle for para recorrer el arreglo y dentro de este se crea una variable randimPosition para guardar un numero aleatorio con el rango de ventas del arreglo y una variable index que guarda el valor de la venta en ese índice del arreglo, luego se le asigna al valor de la venta en ese índice una posición aleatoria en el arreglo y por último se le asigna a la venta en la posición aleatoria el valor de la venta en esa mismo posición. Al finalizar el bucle se crea otro bucle para recorrer e imprimir el arreglo desordenado. 

 

4.5 Diseñar una función que permita ordenar las ventas siendo la primera parte las ventas pares y la segunda parte las ventas impares  

     public static void ordenarVentasParesImpares(int[] ventas) {
        int index;
        for (int i = 0; i < ventas.length - 1; i++) {

            for (int j = i + 1; j < ventas.length; j++) {
                if (ventas[i] % 2 != 0) {
                    index = ventas[i];
                    ventas[i] = ventas[j];
                    ventas[j] = index;
                }
            }
        }
        System.out.println("Ventas ordenadas de forma que los pares van primero y luego los impares");
        for (byte i = 0; i < ventas.length; i++) {
            System.out.println(ventas[i]);
        }
    }

R// Como en el caso de la función ordenarDescendente y ordenarAscendente, se reutiliza el código con los mismos parámetros y variables, pero lo que cambia en este caso es la condicion en el if la cual indica que si el módulo de la división entre la venta en esa posición y el numero 2 es diferente de 0 el valor de la venta en esa posición es un numero impar y si es par no ejecuta el código dentro del if. 

 
 

 

Trabajar con matrices (tablas o arreglos multidimensionales)
5.1 Declarar una matriz 5z8 de tipo Object en una variable llamada lenguajes, a la          primera fila de la matriz lenguajes se debe asignar los siguientes valores en ese orden [NOMBRE, AÑO, AUTOR, DETALLES, FRAMEWORKS]  

     //Matrices 
        Object[][] lenguajes = new Object[5][8];

        lenguajes[0][0] = "NOMBRE";
        lenguajes[0][1] = "AÑO";
        lenguajes[0][2] = "AUTOR";
        lenguajes[0][3] = "DETALLES";
        lenguajes[0][4] = "FRAMEWORK";

 

R// Se crea una matriz de tipo Object denominada lenguajes el cual tiene 5 filas y 8 columnas, en la primera fila se guarda los datos NOMBRE, AÑO, AUTOR, DETALLES, FRAMEWORKS empezando de arriba hacia abajo.  

 

5.2 Realizar una función llamada infoLenguajes que permita llenar la matriz lenguajes con datos por teclado a partir de la segunda fila.  

      public static void infoLenguajes(Object[][] lenguajes) {
        Scanner teclado = new Scanner(System.in);

        for (byte i = 1; i < lenguajes.length; i++) {
            for (byte j = 0; j < lenguajes[i].length; j++) {

                System.out.println("Ingrese el dato para la fila " + i + " y la columna " + j);
                Object dato = teclado.next();

                lenguajes[i][j] = dato;

            }
        }

    }
 

 

R// Se crea una función sin valor de retorno que reciba la matriz como parámetro, en esta función se crea una instancia de la clase Scanner y se le asigna el nombre de teclado para leer los datos por teclado, seguido de esto se crean 2 bucles for para recorrer la matriz, dentro de estos bucles se crea una salida pidiéndole al usuario que ingrese el dato en la fila y columna que se encuentre y se crea una variable de tipo Object para almacenar el dato ingresado por teclado y por último se guarda el dato ingresado en la fila y columna en la que se encuentre la matriz.  

 

5.3 Realizar una función que reciba como parámetro el nombre de un lenguaje y retorna verdadero si este se encuentra dentro de la matriz lenguajes, de lo contrario retorna falso 


       public static boolean verificarNombreLenguaje(Object[][] lenguajes, String lenguaje1) {

        for (byte i = 1; i < lenguajes.length; i++) {
            for (byte j = 0; j < lenguajes[i].length; j++) {

                if (lenguajes[i][j].equals(lenguaje1)) {
                    return true;
                }

            }
        }

        return false;
    }
 

R// Se crea una función que devuelve un tipo de dato boolean y que recibe como parámetros la matriz lenguajes y una variable lenguaje1 de tipo String, se crean los 2 bucles for para recorrer la matriz y se crea un condicional if con la condicion de que si el valor de la matriz lenguajes es igual al lenguaje1 entonces devuelve verdadero y si la condicion no se cumple retorna falso.  

 

 

R// Se llama a la función infoLenguajes en el método main,  se crea la variable de tipo String llamada lenguaje1 en la cual se guarda el nombre de un lenguaje. Se crea los bucles para recorrer la matriz lenguajes e imprimirla, y por último se imprime el valor que retorna la función verificarNombreLenguajes. 

 

 
