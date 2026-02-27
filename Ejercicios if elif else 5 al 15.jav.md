**Ejercicios if elif else 5 al 15.java**

import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.println("--- Ecuación Cuadrática ---");

&nbsp;       System.out.print("a: "); double a = sc.nextDouble();

&nbsp;       System.out.print("b: "); double b = sc.nextDouble();

&nbsp;       System.out.print("c: "); double c = sc.nextDouble();



&nbsp;       double d = Math.pow(b, 2) - 4 \* a \* c;



&nbsp;       if (d > 0) {

&nbsp;           double x1 = (-b + Math.sqrt(d)) / (2 \* a);

&nbsp;           double x2 = (-b - Math.sqrt(d)) / (2 \* a);

&nbsp;           System.out.println("x1 = " + x1 + ", x2 = " + x2);

&nbsp;       } else if (d == 0) {

&nbsp;           System.out.println("x = " + (-b / (2 \* a)));

&nbsp;       } else {

&nbsp;           System.out.println("No tiene soluciones reales.");

&nbsp;       }

&nbsp;   }

}



import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Introduce un número: ");

&nbsp;       int n = sc.nextInt();



&nbsp;       if (n % 2 == 0) {

&nbsp;           System.out.println("Es par");

&nbsp;       } else {

&nbsp;           System.out.println("Es impar");

&nbsp;       }

&nbsp;   }

}



import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Año: ");

&nbsp;       int y = sc.nextInt();



&nbsp;       if ((y % 4 == 0 \&\& y % 100 != 0) || (y % 400 == 0)) {

&nbsp;           System.out.println("Es bisiesto");

&nbsp;       } else {

&nbsp;           System.out.println("No es bisiesto");

&nbsp;       }

&nbsp;   }

}



import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Nombre: "); String nombre = sc.nextLine();

&nbsp;       System.out.print("Edad: "); int edad = sc.nextInt();



&nbsp;       if (edad >= 70) {

&nbsp;           System.out.println(nombre + " tiene prioridad en la fila.");

&nbsp;       } else {

&nbsp;           System.out.println(nombre + " turno normal.");

&nbsp;       }

&nbsp;   }

}



import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("N1: "); double n1 = sc.nextDouble();

&nbsp;       System.out.print("N2: "); double n2 = sc.nextDouble();

&nbsp;       System.out.print("N3: "); double n3 = sc.nextDouble();



&nbsp;       if (n1 >= n2 \&\& n1 >= n3) System.out.println("Mayor: " + n1);

&nbsp;       else if (n2 >= n1 \&\& n2 >= n3) System.out.println("Mayor: " + n2);

&nbsp;       else System.out.println("Mayor: " + n3);

&nbsp;   }

}



import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Lado 1: "); double l1 = sc.nextDouble();

&nbsp;       System.out.print("Lado 2: "); double l2 = sc.nextDouble();

&nbsp;       System.out.print("Lado 3: "); double l3 = sc.nextDouble();



&nbsp;       if (l1 == l2 \&\& l2 == l3) {

&nbsp;           System.out.println("Es un triángulo Equilátero.");

&nbsp;       } else if (l1 == l2 || l1 == l3 || l2 == l3) {

&nbsp;           System.out.println("Es un triángulo Isósceles.");

&nbsp;       } else {

&nbsp;           System.out.println("Es un triángulo Escaleno.");

&nbsp;       }

&nbsp;   }

}



import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Nombre: "); String nom = sc.nextLine();

&nbsp;       System.out.print("Peso (kg): "); double p = sc.nextDouble();

&nbsp;       System.out.print("Altura (m): "); double h = sc.nextDouble();



&nbsp;       double imc = p / (h \* h);

&nbsp;       System.out.println(nom + " tu IMC es " + String.format("%.2f", imc));



&nbsp;       if (imc < 18.5) System.out.println("Categoría: Bajo peso. Come más.");

&nbsp;       else if (imc < 25) System.out.println("Categoría: Normal. ¡Bien!");

&nbsp;       else if (imc < 30) System.out.println("Categoría: Sobrepeso. Haz ejercicio.");

&nbsp;       else System.out.println("Categoría: Obesidad. Ve al médico.");

&nbsp;   }

}





import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("N1: "); double v1 = sc.nextDouble();

&nbsp;       System.out.print("N2: "); double v2 = sc.nextDouble();

&nbsp;       System.out.print("Operación (+,-,\*,/): "); char op = sc.next().charAt(0);



&nbsp;       if (op == '+') System.out.println("Suma: " + (v1 + v2));

&nbsp;       else if (op == '-') System.out.println("Resta: " + (v1 - v2));

&nbsp;       else if (op == '\*') System.out.println("Multiplicación: " + (v1 \* v2));

&nbsp;       else if (op == '/') {

&nbsp;           if (v2 != 0) System.out.println("División: " + (v1 / v2));

&nbsp;           else System.out.println("Error: Div/0");

&nbsp;       } else System.out.println("Opción inválida.");

&nbsp;   }

}



import java.util.Scanner;



public class main{

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Introduce nota (0-100): ");

&nbsp;       int nota = sc.nextInt();



&nbsp;       if (nota >= 90 \&\& nota <= 100) {

&nbsp;           System.out.println("Calificación: A");

&nbsp;       } else if (nota >= 80) {

&nbsp;           System.out.println("Calificación: B");

&nbsp;       } else if (nota >= 70) {

&nbsp;           System.out.println("Calificación: C");

&nbsp;       } else if (nota >= 60) {

&nbsp;           System.out.println("Calificación: D");

&nbsp;       } else if (nota >= 0 \&\& nota < 60) {

&nbsp;           System.out.println("Calificación: F");

&nbsp;       } else {

&nbsp;           System.out.println("Nota no válida.");

&nbsp;       }

&nbsp;   }

}



import java.util.Scanner;



public class Ejercicio14 {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Número del día (1-7): ");

&nbsp;       int dia = sc.nextInt();



&nbsp;       if (dia == 1) System.out.println("Lunes");

&nbsp;       else if (dia == 2) System.out.println("Martes");

&nbsp;       else if (dia == 3) System.out.println("Miércoles");

&nbsp;       else if (dia == 4) System.out.println("Jueves");

&nbsp;       else if (dia == 5) System.out.println("Viernes");

&nbsp;       else if (dia == 6) System.out.println("Sábado");

&nbsp;       else if (dia == 7) System.out.println("Domingo");

&nbsp;       else System.out.println("Error: Solo números del 1 al 7.");

&nbsp;   }

}





mport java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Lado A: "); double a = sc.nextDouble();

&nbsp;       System.out.print("Lado B: "); double b = sc.nextDouble();

&nbsp;       System.out.print("Lado C: "); double c = sc.nextDouble();



&nbsp;       if (a + b > c \&\& a + c > b \&\& b + c > a) {

&nbsp;           if (a == b \&\& b == c) System.out.println("Equilátero válido.");

&nbsp;           else if (a == b || a == c || b == c) System.out.println("Isósceles válido.");

&nbsp;           else System.out.println("Escaleno válido.");

&nbsp;       } else {

&nbsp;           System.out.println("No forman un triángulo.");

&nbsp;       }

&nbsp;   }

}











**Ejercicios if ternario 5 al 15.java**

import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("a, b, c: ");

&nbsp;       double a = sc.nextDouble(), b = sc.nextDouble(), c = sc.nextDouble();

&nbsp;       double d = Math.pow(b, 2) - 4 \* a \* c;



&nbsp;       String resultado = (d > 0) ? "Dos raíces: " + ((-b + Math.sqrt(d)) / (2 \* a)) + " y " + ((-b - Math.sqrt(d)) / (2 \* a)) :

&nbsp;                         (d == 0) ? "Raíz única: " + (-b / (2 \* a)) : "Sin raíces reales";

&nbsp;       System.out.println(resultado);

&nbsp;   }

}



import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Número: ");

&nbsp;       int n = sc.nextInt();

&nbsp;       System.out.println(n % 2 == 0 ? "Es Par" : "Es Impar");

&nbsp;   }

}



import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Año: ");

&nbsp;       int y = sc.nextInt();

&nbsp;       System.out.println(((y % 4 == 0 \&\& y % 100 != 0) || (y % 400 == 0)) ? "Bisiesto" : "No bisiesto");

&nbsp;   }

}



import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Nombre: "); String nom = sc.nextLine();

&nbsp;       System.out.print("Edad: "); int ed = sc.nextInt();

&nbsp;       System.out.println(ed >= 70 ? nom + " tiene PRIORIDAD" : nom + " espera turno normal");

&nbsp;   }

}



import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("N1, N2, N3: ");

&nbsp;       double n1 = sc.nextDouble(), n2 = sc.nextDouble(), n3 = sc.nextDouble();

&nbsp;       double mayor = (n1 >= n2 \&\& n1 >= n3) ? n1 : (n2 >= n3 ? n2 : n3);

&nbsp;       System.out.println("El mayor es: " + mayor);

&nbsp;   }

}



import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Lados: ");

&nbsp;       double l1 = sc.nextDouble(), l2 = sc.nextDouble(), l3 = sc.nextDouble();

&nbsp;       String tipo = (l1 == l2 \&\& l2 == l3) ? "Equilátero" : (l1 == l2 || l1 == l3 || l2 == l3 ? "Isósceles" : "Escaleno");

&nbsp;       System.out.println("Tipo: " + tipo);

&nbsp;   }

}



import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Nombre: "); String n = sc.nextLine();

&nbsp;       System.out.print("Peso y Altura: ");

&nbsp;       double p = sc.nextDouble(), h = sc.nextDouble();

&nbsp;       double imc = p / (h \* h);

&nbsp;       String cat = (imc < 18.5) ? "Bajo peso" : (imc < 25 ? "Normal" : (imc < 30 ? "Sobrepeso" : "Obesidad"));

&nbsp;       System.out.println(n + " tiene " + cat + " (IMC: " + String.format("%.2f", imc) + ")");

&nbsp;   }

}



import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("N1, N2 y Op: ");

&nbsp;       double n1 = sc.nextDouble(), n2 = sc.nextDouble();

&nbsp;       char op = sc.next().charAt(0);

&nbsp;       Object res = (op == '+') ? n1+n2 : (op == '-') ? n1-n2 : (op == '\*') ? n1\*n2 : (op == '/' \&\& n2 != 0) ? n1/n2 : "Error";

&nbsp;       System.out.println("Resultado: " + res);

&nbsp;   }

}



import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Nota (0-100): ");

&nbsp;       int nota = sc.nextInt();

&nbsp;       char letra = (nota >= 90) ? 'A' : (nota >= 80 ? 'B' : (nota >= 70 ? 'C' : (nota >= 60 ? 'D' : 'F')));

&nbsp;       System.out.println("Calificación: " + letra);

&nbsp;   }

}



import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Día (1-7): ");

&nbsp;       int d = sc.nextInt();

&nbsp;       String dia = (d==1)?"Lun":(d==2)?"Mar":(d==3)?"Mie":(d==4)?"Jue":(d==5)?"Vie":(d==6)?"Sab":(d==7)?"Dom":"Invalido";

&nbsp;       System.out.println(dia);

&nbsp;   }

}



import java.util.Scanner;



public class main {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Lados A, B, C: ");

&nbsp;       double a = sc.nextDouble(), b = sc.nextDouble(), c = sc.nextDouble();

&nbsp;       String res = (a+b>c \&\& a+c>b \&\& b+c>a) ? ((a==b \&\& b==c) ? "Equilátero" : (a==b || a==c || b==c ? "Isósceles" : "Escaleno")) : "No es triángulo";

&nbsp;       System.out.println(res);

&nbsp;   }

}





**EJERCICIOS IF ELSE 5 al 15.java**

import java.lang.Math;

public class Main {

&nbsp;   public static void main(String\[] args) {



&nbsp;       Scanner sc = new Scanner(System.in);



&nbsp;       System.out.print("Ingrese a: ");

&nbsp;       double a = sc.nextDouble();



&nbsp;       System.out.print("Ingrese b: ");

&nbsp;       double b = sc.nextDouble();



&nbsp;       System.out.print("Ingrese c: ");

&nbsp;       double c = sc.nextDouble();



&nbsp;       double disc = Math.pow(b, 2) - 4 \* a \* c;



&nbsp;       if (disc > 0) {

&nbsp;           double x1 = (-b + Math.sqrt(disc)) / (2 \* a);

&nbsp;           double x2 = (-b - Math.sqrt(disc)) / (2 \* a);

&nbsp;           System.out.println("x1: " + x1 + ", x2: " + x2);

&nbsp;       } else if (disc == 0) {

&nbsp;           double x = -b / (2 \* a);

&nbsp;           System.out.println("x: " + x);

&nbsp;       } else {

&nbsp;           System.out.println("No tiene raíces reales.");

&nbsp;       }



&nbsp;   }

&nbsp;   }



import java.util.Scanner;

