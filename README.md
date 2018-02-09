# RECURSIVIDAD-FIBONACCI-JAVA-PYTHON-

Como un método de definir un proceso a través del uso de premisas
 que no dan más información 
que el método en sí mismo o que utilizan 
los mismos términos que ya aparecen en su nombre, 
por ejemplo cuando 
se dice que la definición de algo es ese algo mismo.

La recursividad es
 una técnica muy utilizada en programación informática. 
Se suele utilizar  para resolver 
problemas cuya solución se puede hallar 
resolviendo el mismo problema, pero para un caso 
de tamaño menor.



CODIGO EN JAVA


public class CalculoFibonacci
 {

// declaración recursiva del método fibonacci
 public long fibonacci( long numero )
 {
 if ( ( numero == 0 ) || ( numero == 1 ) ) // casos base
 return numero;
 else // paso recursivo
 return fibonacci( numero - 1 ) + fibonacci( numero - 2 );
 } // fin del método fibonacci

 public void mostrarFibonacci()
 {
 for ( int contador = 0; contador <= 10; contador++ )
 System.out.printf( "Fibonacci de %d es: %d\n", contador,
 fibonacci( contador ) );
 } // fin del método mostrarFibonacci

public static void main( String args[] )
 {
 CalculoFibonacci calculoFibonacci = new CalculoFibonacci();
 calculoFibonacci.mostrarFibonacci();
 } // fin de main



 } // fin de la clase CalculoFibonacci
 
 https://www.dropbox.com/s/h3f7bpqmrr1557o/JAVCORR.png?dl=0
 
 https://www.dropbox.com/s/ekgvuptcge4vj6j/PY%20%282%29.png?dl=0
 
 
 
 
 
 
 
 
 
 
