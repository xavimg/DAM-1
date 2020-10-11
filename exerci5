import java.util.Scanner;

public class ExerciciInicial5 {

    public static void main(String[] args) {
        Scanner read = new Scanner(System.in);

        double preuVolks = 73490;
        int model;
        double km;

        System.out.println("Quin model de Volkswagen tens [1] o [2]");
        model = read.nextInt();

        System.out.println("Quants KM portes ?");
        km = read.nextInt();

        if (model == 1) {
            preuVolks = preuVolks - (0.00001 * km);
            System.out.println("El preu final del model 1 es : " + preuVolks);

        } else if (model == 2) {
            preuVolks = preuVolks + 20000;
            preuVolks = preuVolks - (0.00001 * km);
            System.out.println("El preu final del model 2 es : " + preuVolks);
        }
    }
}
