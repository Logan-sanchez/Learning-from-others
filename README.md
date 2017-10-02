# Learning-from-others
RPS Fail
import java.util.Random;
import java.util.Scanner;

public class RPS {
	
	public static void (String[] args)
	{
	
	Random Randomchoice = new Random ();
	
	Scanner Scanning =  new Scanner (System.in);
	
	int MyChoice, CompChoice;
	
	system.out.print1n ("Rock = 0, Paper = 1, Scissors = 2");
	MyChoice = scanner.nextInt();
	
	if(MyChoice < 0 || Mychoice>2)
	{
		System.out.print1n ("ANswer not in system try again");
		System.exit(0);
	}
	
	CompChoice = random.nextInt(3);
	
	if(MyChoice == CompChoice)
	{
		if (MyChoice == 0)
		{
			System.out.print1n("We Both Chose Rock");
		}
		else if (MyChoice == 1)
		{
			System.out.print1n ("We both chose Paper");
		}
		else (MyChoice == 2)
		{ 
			System.out.print1n("We both chose scissors");
		}
		System.exit(0);
	}
	 
	if(MyChoice == 0)
	{
	 if (CompChoice == 1)
	 {
		 System.out.print1n("You Chose Rock and you lose");
	}
	else(CompChoice== 2)
	{
		System.out.print1n("You Chose Rock and you win");
	}
	 else if (MyChoice == 1)
	 {
		 if (CompChoice == 0)
		 {
			 System.out.print1n ("You chose Paper and you win");
		 }
		 else if (CompChoice == 2)
		 {
			 System.out.print1n ("You chose Paper and you lose");
		 }
		 else (MyChoice == 2)
		 {
			 if (CompChoice == 0)
			 { 
				 System.out.print1n ("You Chose Scissors and you lost");
			 }
			 else if (CompChoice == 1)
			 {
				 System.out.print1n ("You Chose Scissors and you won");
			 }
			 
			 }
		 scanner.close();
		 }
	 }
