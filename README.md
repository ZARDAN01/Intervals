# Intervals
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in); // Объявляем Scanner


        int size = input.nextInt(); // Читаем с клавиатуры размер массива и записываем в size
        int array[] = new int[0]; // Создаём массив int размером в size
        System.out.println("Insert array elements:");
        /*Пройдёмся по всему массиву, заполняя его*/


            int sum = input.nextInt();
            int value = input.nextInt();
        int a;



        System.out.print("Inserted array elements:");
        
            {
                for(a=sum; a<=value;a++)
                    System.out.println(a);

            }
            System.out.print(" " + array[a]); // Выводим на экран, полученный массив

        System.out.println();
    }
}


























import java.util.Scanner;

public class Main2 {

    protected static int[] number1;
    protected static int[] number2;
    protected static int[] number4;
    protected static int[] number3;


    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.println("количество массива");
        int size = input.nextInt();
        number1 = new int[size];
        System.out.println("ввести элементы массива");
        for (int i = 0; i < size; i++) {
            number1[i] = input.nextInt();
        }
        System.out.print("Сам массив: ");
        for (int i = 0; i < size; i++) {
            System.out.print(number1[i] + " ");
        }
        System.out.println();
        System.out.println("заполним второй массив ");
        number2 = new int[size];
        for (int i = 0; i < size; i++) {
            number2[i] = input.nextInt();
        }
        System.out.print("Сам массив: ");
        for (int i = 0; i < size; i++) {
            System.out.print(number2[i] + " ");
        }
        System.out.println();
        System.out.println("заполним второй массив ");
        number3 = new int[size];
        for (int i = 0; i < size; i++) {
            number3[i] = input.nextInt();
        }
        System.out.print("Сам массив: ");
        for (int i = 0; i < size; i++) {
            System.out.print(number3[i] + " ");
        }
        System.out.println();
        System.out.println("заполним второй массив ");
        number4 = new int[size];
        for (int i = 0; i < size; i++) {
            number4[i] = input.nextInt();
        }
        System.out.print("Сам массив: ");
        for (int i = 0; i < size; i++) {
            System.out.print(number4[i] + " ");
        }

            int[] number3 = new int[number1.length];
            int count = 0;

            for (int i = 0; i < number1.length ; i++) {
                if(number1[i] == number2[i]) {
                    number3[count] = number1[i];
                    count++;
                }
            }

            int[] number4 = new int[count];
            System.arraycopy(number3,0,number4, 0, count);

        }
        // тут я должен начать их сравнивать, но из-за
        // множества новой информации, с таким вроде бы
        // простым вопросом, я через гугл не разобрался
    }
