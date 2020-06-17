#import java.util.*;
class SumOfSumsOfDigitsInCyclicOrder {

	public int sumOfSumsOfDigits(int x)
  {
		String n = String.valueOf(x);
		int sum = 0;
		
		for (int i = 0; i < n.length(); i++) 
    {
			for (int j = i; j < n.length(); j++) 
      {
                sum += Integer.parseInt(String.valueOf(n.charAt(j)));
			}
		}
		
		return sum;
	}
}
