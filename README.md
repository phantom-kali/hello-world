# hello-world
just another repository

/**
 * 
 */
package Analyzer;

import java.util.Scanner;

/**
 * @author fidel
 *
 */
public class language_analysis {
	
	static Scanner scanner = new Scanner(System.in);
	public String Tribe,Fatherstribe;
	public int age,selection;

	/**
	 * @param args
	 */
		
		public void Selection () {
			
			System.out.println("Enter the language you speak: ");
			Tribe=scanner.nextLine();
			
			System.out.println("Enter the language your Father speaks: ");
			Fatherstribe=scanner.nextLine();	
			
			while(Tribe.equalsIgnoreCase(Fatherstribe)) {
				System.out.println("You are a " + " " + Tribe);
				System.exit(0);
				
			}
			
			while(Tribe!=Fatherstribe) {
				
				System.out.print("Enter your age: ");
				age=scanner.nextInt();
				
				if(age<=18) {
					
					System.out.println("You are a " + " " + Fatherstribe);
					
				}
				
				else if(age==18){
					
					System.out.println("You are a " + " " + Tribe);				
				}
				
				else{
					
					System.out.println("You are a " + " " + Tribe);				
				}

				System.exit(0);
				
			}
		}

	
	public static void main(String[] args) {
		// TODO Auto-generated method stub 
		
		language_analysis analysis = new language_analysis();
    analysis.Selsction();
		
	}

}

