/**
*<This class keeps track of temperatures entered by a user that are higher than 90 >
*
*@author Destini Anderson
*April 6, 2017
*/
public class HighTemp
{

	/**
	 * @param args
	 */
	public static void main(String[] args)
	{
		Scanner inputdevice = new Scanner(System.in);
		int tempsEntered;
		
		
		System.out.println("How many temperatures will you enter?");
		tempsEntered = inputdevice.nextInt();
		
		int temp = 0;
		
		
		do
		{
			int higherThanNinety = 0;
			
			System.out.println("\nPlease enter a temperature: ");
			temp = inputdevice.nextInt();
			
			if(temp >= 90)
			{
				System.out.println("The number of temperatures higher "
						+ "than 90 was " + higherThanNinety + ".");
			}
			
			
		
		} 
		while (temp >= 90);
			
			
		
		
		

	}

}
