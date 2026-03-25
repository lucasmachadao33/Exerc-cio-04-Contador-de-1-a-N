import java.util.Scanner;

public class Contador {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Digite N: ");
        int n = sc.nextInt();

        // Verificação de valor inválido
        if (n <= 0) {
            System.out.println("Valor inválido. N deve ser maior que zero.");
        } else {
            int i = 1; // inicializa contador

            while (i <= n) {
                System.out.println(i);
                i++; // incrementa dentro do laço
            }

            System.out.println("Contagem concluída.");
        }

        sc.close();
    }
}
