# Primera-calculadora-
Prueba 
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int num1, num2;
        System.out.print("Ingrese el primer número: ");
        num1 = scanner.nextInt();
        System.out.print("Ingrese el segundo número: ");
        num2 = scanner.nextInt();
        System.out.println("Números leídos: " + num1 + " y " + num2);
        System.out.println("Suma: " + (num1 + num2));
        System.out.println("Resta: " + (num1 - num2));
        System.out.println("Producto: " + (num1 * num2));
        try {
            System.out.println("División: " + (num1 / num2));
        } catch (ArithmeticException e) {
            System.out.println("Error: no se puede dividir por cero");
        }
        int[] numeros = {1, 2, 3, 4, 5};
        System.out.print("Contenido del array: ");
        for (int i = 0; i < numeros.length; i++) {
            System.out.print(numeros[i] + " ");
        }
        System.out.println();
    }
}
