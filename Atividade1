# avalia-oimport java.util.Scanner;

public class MediaEscolar {
    public static void main(String[] args) {
        Scanner entrada = new Scanner(System.in);
        double[] notas = new double[8];

        // Entrada das notas
        System.out.println("Digite as 8 notas do aluno:");
        for (int i = 0; i < 8; i++) {
            System.out.print("Nota " + (i + 1) + ": ");
            notas[i] = entrada.nextDouble();
        }

        // Cálculo das médias
        double media1Bim = (notas[0] + notas[1]) / 2;
        double media2Bim = (notas[2] + notas[3]) / 2;
        double media1Sem = (media1Bim + media2Bim) / 2;

        double media3Bim = (notas[4] + notas[5]) / 2;
        double media4Bim = (notas[6] + notas[7]) / 2;
        double media2Sem = (media3Bim + media4Bim) / 2;

        double mediaFinal = (media1Sem + media2Sem) / 2;

        // Saída
        System.out.println("\nResultados:");
        System.out.println("1º Bimestre: " + media1Bim);
        System.out.println("2º Bimestre: " + media2Bim);
        System.out.println("1º Semestre: " + media1Sem);
        System.out.println("------------------------");
        System.out.println("3º Bimestre: " + media3Bim);
        System.out.println("4º Bimestre: " + media4Bim);
        System.out.println("2º Semestre: " + media2Sem);
        System.out.println("------------------------");
        System.out.println("Média Final: " + mediaFinal);

        entrada.close();
    }
}-01
