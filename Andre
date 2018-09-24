/*
NAME: Andre Shibata (Nobu)
DATE: 9/18/2018
PROJECT NAME: Windchill
DESCRIPTION: In this project, user's inputs of temperature in fahrenheit and 
wind speed in miles per hour are being used to calculate the windchill, based
on a windchill formula provided by the youtube video cited below.
*/
import java.util.Scanner;

public class windchill {

	public static void main(String[] args) {
		
		Scanner scan = new Scanner(System.in);
		//In the statement above, a new scanner object called scan was created.
		System.out.print("Enter Temperature: ");
		double temperature = scan.nextDouble();
		//In the statement above, a method from the Scanner class was used, to ask for an user input of a double. 
		System.out.print("Enter the Wind Speed: ");
		double wspeed = scan.nextDouble();
		//CITATION: https://www.youtube.com/watch?v=M0p4i444wrs
		//DETAILS: The formula for wind chill below was taken from this youtube video above.
		double windchill = 35.74 + (0.6215 * temperature) + ((Math.pow( wspeed, 0.16)) * ((0.4275*temperature)-35.75));
		System.out.println("At " + temperature + " degrees, with a wind speed of " + wspeed +
		" miles per hour the windchill is: " + windchill + " degrees.");

		
		}
}
