# Ejercicio-Grupo-de-Estudiantes
De pseudocógido pasado a JAVA
package grupodeestudiantes;


import java.util.Scanner;

public class GrupoDeEstudiantes {
  /*Un profesor desea saber que porcentajes de hombres y que porcentajes de mujeres hay en un grupo de estudiantes.
  */  
   
 public static void main(String[] args) {
  int porc; 
  int cantidad;
  int hombres;
  int mujeres;
  Scanner porcentaje = new Scanner (System.in);
  System.out.println("Imprimir la cantidad de alumnos");
  cantidad = porcentaje.nextInt();
  System.out.println("Cantidad de hombres");
  hombres = porcentaje.nextInt();
  System.out.println("Cantidad de mujeres");
  mujeres = porcentaje.nextInt();
  {
porc = hombres*100/cantidad;
porc = mujeres*100/cantidad;
  }
  System.out.println("Imprimir porcentaje de hombres"+ hombres );
  System.out.println("Imprimir porcentaje de mujeres"+ mujeres);
 }
  
}
