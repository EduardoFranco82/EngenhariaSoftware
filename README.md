# EngenhariaSoftware
import java.util.Locale;
import java.util.Scanner;

public class Program {

	public static void main(String[] args) {
		Locale.setDefault(Locale.US);
		Scanner sc = new Scanner(System.in);
		
		int codigo, quantidade;
		double total;
		
		System.out.println("DIGITE O CODIGO E A QUANTIDADE DO PRODUTO");
		codigo = sc.nextInt();
		quantidade = sc.nextInt();
		
		if (codigo == 1) {
			total = quantidade * 4.00;
			}
		else if ( codigo == 2) {
			total = quantidade * 4.50;
		}
		else if ( codigo == 3) {
			total = quantidade * 5.00;
		}
		else if ( codigo == 4) {
			total = quantidade * 2.00;
		}
		else {
			total = quantidade * 1.50;
		}
		
		System.out.println("TOTAL : R$ " + total);
		
		
		sc.close();

	}

}
