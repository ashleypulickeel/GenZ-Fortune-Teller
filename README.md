# GenZ-Fortune-Teller
import java.util.*;
import java.util.Scanner;

public class GenZ {

	public static void main(String[] args) {
		//main method to call options methods. 
		Scanner kb= new Scanner (System.in);
		
		while(true) {
			
		System.out.println("Welcome to the GenZ Fortune Teller! Please choose a category.");
		System.out.println("1. Love");
		System.out.println("2. Life");
		System.out.println("3. Luck");
		int option = kb.nextInt();
		
		if(option==1) {
		option1();	
	}	
		if (option==2) {
		option2();
	}
		if(option==3) {
		option3();
	}
		}
	}
	public static void option1 (){
		Scanner ka = new Scanner(System.in);
		System.out.println("1. Does my crush like me back?");
		System.out.println("2. What is love?");
		System.out.println("3. Will I find true love?");
		System.out.println("4. How will I find a boyfriend?");
		
		int love= ka.nextInt();
		
		if(love ==1) {
			
			System.out.println("Defintely...");
					System.out.println("");
					System.out.println("");
					System.out.println("");
					System.out.println("...in your dreams =)");
		}
		
		if(love==2) {
			System.out.println("Baby don't hurt me, don't hurt me, no more");
		}
		if (love==3) {
			System.out.println("maybe, if don't spend 4 hours on tiktok everyday");
		}	
		if (love==4) {
			
			System.out.println("Make a milkshake and that'll bring all the boys to the yard");
		}
	}
	
	public static void option2() {
		Scanner ki = new Scanner(System.in);
		System.out.println("1. Will I be rich?");
		System.out.println("2. When will I die?");
		System.out.println("3. Will I be happy?");
		System.out.println("4. What will be my greatest achievement?");
		
		
int life= ki.nextInt();
		
		if(life ==1) {
			
			System.out.println("manifest it <3");
		}
		
		if (life==2) {
			
			System.out.println("When you stop breathing");
		}
		if (life==3) {
			
			System.out.println("Not with that attitude");
		}
		
		if (life==4) {
			
			System.out.println("So far, it's been converting oxygen into carbon dioxide");
		}
	}
	
	
public static void option3() {
		Scanner ko= new Scanner(System.in);
		
		
		System.out.println("1. When will I win the lottery?");
		System.out.println("2. Will I win the Roll Up The Rim?");
		System.out.println("3. Will I be viral on TikTok? ");
		System.out.println("4. Will my favourite celebrity respond to my DM?");
		
		int luck = ko.nextInt();
		if(luck==1) {
			
			System.out.println("When you get the winning numbers");
		}
		
		if(luck==2) {
			System.out.println("Whenever it doesn't say play again");
		}
		
		if(luck==3) {
			System.out.println("Only if you're Charli, we stan a queen");
			
		}
		
		if(luck==4) {
			
			System.out.println("Depends how old you are");
			
		}
	}

}
