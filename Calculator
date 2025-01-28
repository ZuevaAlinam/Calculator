import java.util.Scanner;

public class Calculator {

    public static void main(String[] args) {
        System.out.println("Здравствуйте, многоуважаемый пользователь!" +"\n"
                + "Данная программа не более, чем простой калькулятор с примитивными функциями :("+"\n"
                +"Приятного пользования!");

        Scanner in  = new Scanner(System.in);

        double a = in.nextDouble();
        String userSymb = in.next();
        double b  = in.nextDouble();

        switch (userSymb){
            case "+":
                System.out.println(addition(a,b));
                break;
            case  "-":
                System.out.println(subtraction(a,b));
                break;
            case "*":
                System.out.println(multiplication(a,b));
                break;
            case "/":
                division(a,b);
                break;
            default: System.out.println("К сожалению данная функция не реализована");
        }

    }
    public static double addition(double a, double b){
        return a+b;
    }
    public static double subtraction( double a, double b){
        return a-b;
    }
    public static double multiplication(double a, double b){
        return a*b;
    }
    public static void division( double a, double b){
        if(b==0) {
            System.out.println("Ошибка: деление на нуль не возможно!");

        }
        else
            System.out.println(a/b);
    }
}
