# Sobremesa-Favorita
Sobremesa Favorita
import java.util.Locale;
import java.util.Scanner;

public class Teste {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
				
        String C;
		int S;
		

		do
		{	
			
		System.out.println("Dúvido descobrir minha sobremesa favorita?? Digite o número da sobremesa : " );
		System.out.println(" 1 = Rocambole");
		System.out.println(" 2 = Mousse");
		System.out.println(" 3 = Torta Holandesa");
		System.out.println(" 4 = Bolo ");
		S = sc.nextInt();
			
		if (S!=3) {
			System.out.println("Que pena, acho que não me conhece tão bem assim ):");
		} 
		else if ((S>5)||(S<0)){
			System.out.println("Número inválido");
		}
		else {
		System.out.println("Uall, excelente escolha (: amo Torta Holandesa");
		}
		
		System.out.print("Deseja tentar de novo ? se sim S, se não N " );
		C = sc.next();
	
		} while((C != "N") || (C != "n"));
		
		sc.close();
		
    }
}
