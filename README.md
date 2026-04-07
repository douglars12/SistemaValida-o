 import java.util.Scanner;

public class sistemaValidacao {

    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        // Entrada de dados
        System.out.print("Digite o nome do candidato: ");
        String nome = scanner.nextLine();

        System.out.print("Digite a idade: ");
        int idade = scanner.nextInt();

        System.out.print("Digite a nota da prova: ");
        double nota = scanner.nextDouble();

        // Validação do processo seletivo
        if (idade >= 18 && nota >= 7.0) {
            System.out.println("\nCandidato: " + nome);
            System.out.println("Status: APROVADO ✅");
        } else {
            System.out.println("\nCandidato: " + nome);
            System.out.println("Status: REPROVADO ❌");
        }

        scanner.close();
    }
 {
    
}
}
