import java.util.Scanner;
import java.io.IOException;

public class Main {
    public static void main(String[] args) throws IOException {

        Scanner ler = new Scanner(System.in);
        char esc;
        int opcao;
        long chamado;
        String email;
        long telefone;
        String sn;
        char tv;
        while (true) {


            System.out.print(
                    "Selecione uma opção\n" +
                            "1) abrir chamado\n" +
                            "2) atendimento técnico\n" +
                            "qual é tua escolha?\n"
            );

            opcao = ler.nextInt();
            ler.nextLine(); // limpa buffer

            if (opcao == 1) {
                System.out.print(
                        "Informe os seguintes dados:\n" +
                                "o E-mail corporativo\n");
                email = ler.nextLine();
                System.out.printf("Telefone corporativo\n");
                telefone = ler.nextLong();
                ler.nextLine(); // LIMPA O ENTER
                System.out.printf("numero de serie:\n");
                sn = ler.nextLine();
                System.out.printf("suas informaçoes estáo corretas?:\nEMAIL:%s\nTELEFONE:%d\nSN:%s\n", email, telefone, sn);
                tv = (char) System.in.read();
                ler.nextLine();
                System.in.read();
                if (tv == 's') {
                    System.out.printf("Fico à disposição para verificar se posso ajudar em algo mais. Poderia, por gentileza,\n confirmar se o chamado foi solucionado ou\n se ainda há necessidade de apoio?");

                    break; // encerra tudo

                }else{
                    System.out.print(
                            "Informe os seguintes dados:\n" +
                                    "o E-mail corporativo\n");
                    email = ler.nextLine();
                    System.out.printf("Telefone corporativo\n");
                    telefone = ler.nextLong();
                    System.out.printf("numero de serie:\n");
                    sn = ler.nextLine();
                    System.out.printf("suas informaçoes estáo corretas?:\n%s\n%d\n%s\n", email, telefone, sn);
                    tv = (char) System.in.read();
                    System.in.read();
                    break;
                }
            } else {

                System.out.print(
                        "Possui Acesso ao Portal Simpress?\n" +
                                "(se não, favor abrir chamado no help desk para criação de acesso)\n"
                );

                esc = (char) System.in.read();
                System.in.read(); // entrada de dados

                if (esc == 's') {
                    System.out.print("passo a passo atend tec\n");
                    System.out.print("insira o numero do chamado:\n");
                    chamado = ler.nextLong();
                    System.out.printf("numero do chamado é:%d", chamado);

                    break; // encerra
                } else {
                    // 👇 AQUI executa a OPÇÃO 1
                    System.out.print(
                            "Informe os seguintes dados:\n" +
                                    "o E-mail corporativo\n");
                    email = ler.nextLine();
                    System.out.printf("Telefone corporativo\n");
                    telefone = ler.nextLong();
                    ler.nextLine(); // LIMPA O ENTER
                    System.out.printf("numero de serie:\n");
                    sn = ler.nextLine();
                    System.out.printf("suas informaçoes estáo corretas?:\n%s\n%d\n%s\n", email, telefone, sn);
                    break; // encerra
                }
            }
        }
    }
}
