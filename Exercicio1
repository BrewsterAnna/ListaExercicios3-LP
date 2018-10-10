//1.	Faça um algoritmo que leia uma sequência de caracteres terminada por um ponto 
//e mostre o numero de vogais da frase.
package listaexercicio3;

import java.util.Scanner;

public class Exercicio1 {
    public static void main(String[] args) {
        final char FIM = '.';
        String linha;
        Scanner entrada = new Scanner(System.in);
        char car;
        int contVogal = 0, pos = 0;
        
        System.out.println("Entre com a frase terminada em ponto");
        linha = entrada.nextLine();
        car = linha.charAt(pos);
        while (car != FIM) {
            switch (car) {
                case 'a': case 'A':
                case 'e': case 'E':
                case 'i': case 'I':
                case 'o': case 'O':
                case 'u': case 'U':
                    contVogal++;
            }
            pos++;
            car = linha.charAt(pos);
        }
        System.out.println("Número de vogais = " + contVogal);
    }
}
